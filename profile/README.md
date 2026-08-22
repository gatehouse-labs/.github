<div align="center">

<img src="assets/logos/gatehouse-labs-logo.svg" width="280" alt="Gatehouse Labs" />

<sub>A personal lab for AI-assisted software, built with Claude</sub>

</div>

<br/>

Gatehouse Labs is where I build tools with Claude and figure out what AI-assisted
development actually looks like in practice — not just prompting for snippets, but
using Claude Code and MCP to design, build, and review working software end to end.

The flagship project right now is a suite of firewall-engineering tools built on
Fortinet FortiManager / FortiAnalyzer: dashboards, reporting, and AI-driven rule
review and design. More repos will land here as the lab grows.

<br/>

<table align="center">
<tr>
<td align="center" width="25%">
<img src="assets/logos/4thealth-mark.svg" width="72" /><br/>
<b>4tHealth</b><br/>
<sub>Fabric health dashboard</sub><br/><br/>
<a href="https://github.com/gatehouse-labs/4thealth">View repo →</a>
</td>
<td align="center" width="25%">
<img src="assets/logos/4tlog-mark.svg" width="72" /><br/>
<b>4tLog</b><br/>
<sub>Pulling log files from FortiAnalyzer</sub><br/><br/>
<a href="https://github.com/gatehouse-labs/4tLog">View repo →</a>
</td>
<td align="center" width="25%">
<img src="assets/logos/4tanalyst-mark.svg" width="72" /><br/>
<b>4tAnalyst</b><br/>
<sub>AI-assisted rule request review</sub><br/><br/>
<a href="https://github.com/gatehouse-labs/4tAnalyst">View repo →</a>
</td>
<td align="center" width="25%">
<img src="assets/logos/4thealthplus-mark.svg" width="72" /><br/>
<b>4tHealth+</b><br/>
<sub>Health + policy hygiene + AI rule design</sub><br/><br/>
<a href="https://github.com/gatehouse-labs/4thealth-plus">View repo →</a>
</td>
</tr>
</table>

<br/>

## Built with Claude

Every repo here is designed and built in collaboration with Claude (Anthropic's AI),
using [Claude Code](https://claude.com/claude-code) for agentic development — planning
changes, writing and reviewing code, and iterating against real Fortinet APIs — and
[MCP](https://modelcontextprotocol.io) to connect Claude directly to those APIs and to
FortiManager/FortiAnalyzer data. 4tAnalyst and 4tHealth+ go a step further and use an
LLM at runtime, via MCP, to review and draft firewall rule changes before a human ever
sees them.

This is also a proving ground for going deeper with Anthropic's tools and, over time,
for pursuing Anthropic certifications as they become available.

## The Fortinet suite

| | |
|---|---|
| **4tHealth** | Fabric health dashboard for FortiManager-managed devices. |
| **4tLog** | Pulls and browses log files from FortiAnalyzer (7.4.x and 7.6.x). |
| **4tAnalyst** | AI assistant for reviewing Fortinet/FortiManager firewall change requests. |
| **4tHealth+** | Read-only network operations dashboard for FortiGate/FortiManager — health monitoring, policy hygiene, CIS device audits, and change validation, with AI-assisted rule design added on top. |

All four run independently — 4tHealth+ is a newer, more capable sibling, not a replacement
for the other two.

<br/>

<div align="center">
<sub>A personal portfolio project — not affiliated with or endorsed by Fortinet or Anthropic.</sub>
</div>
