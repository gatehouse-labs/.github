<div align="center">

<img src="assets/logos/gatecrest-labs-logo.svg" width="280" alt="Gatecrest Labs" />

<sub>A portfolio of firewall-engineering tools built on Fortinet FortiManager / FortiAnalyzer</sub>

</div>

<br/>

Gatecrest Labs isn't a company — it's a name for a set of tools built to explore what
AI-assisted workflows look like for firewall engineers: dashboards, reporting, and
AI-driven rule review and design, all working against FortiManager/FortiAnalyzer.

<br/>

<table align="center">
<tr>
<td align="center" valign="top" width="20%">
<img src="assets/logos/4thealth-mark.svg" width="72" alt="4tHealth" /><br/>
<b>4tHealth</b><br/>
<sub>Fabric health dashboard</sub><br/><br/>
<a href="https://github.com/gatecrest-labs/4thealth">View repo →</a>
</td>
<td align="center" valign="top" width="20%">
<img src="assets/logos/4tlog-mark.svg" width="72" alt="4tLog" /><br/>
<b>4tLog</b><br/>
<sub>Pulling log files from FortiAnalyzer</sub><br/><br/>
<a href="https://github.com/gatecrest-labs/4tLog">View repo →</a>
</td>
<td align="center" valign="top" width="20%">
<img src="assets/logos/4tanalyst-mark.svg" width="72" alt="4tAnalyst" /><br/>
<b>4tAnalyst</b><br/>
<sub>AI-assisted rule request review</sub><br/><br/>
<a href="https://github.com/gatecrest-labs/4tAnalyst">View repo →</a>
</td>
<td align="center" valign="top" width="20%">
<img src="assets/logos/4thealthplus-mark.svg" width="72" alt="4tHealth+" /><br/>
<b>4tHealth+</b><br/>
<sub>Health + policy hygiene + AI rule design</sub><br/><br/>
<a href="https://github.com/gatecrest-labs/4thealth-plus">View repo →</a>
</td>
<td align="center" valign="top" width="20%">
<img src="assets/logos/4texecutive-mark.svg" width="72" alt="4tExecutive" /><br/>
<b>4tExecutive</b><br/>
<sub>Executive rollup dashboard</sub><br/><br/>
Coming soon
</td>
</tr>
</table>

<br/>

## About the suite

| | |
|---|---|
| **4tHealth** | Fabric health dashboard for FortiManager-managed devices. |
| **4tLog** | Pulls and browses log files from FortiAnalyzer (7.4.x and 7.6.x). |
| **4tAnalyst** | AI assistant for reviewing Fortinet/FortiManager firewall change requests. |
| **4tHealth+** | Read-only network operations dashboard for FortiGate/FortiManager — health monitoring, policy hygiene, CIS device audits, and change validation, with AI-assisted rule design added on top. |
| **4tExecutive** | Read-only executive dashboard that rolls up metrics from the other tools into one view, without giving executives access to the operational tools themselves. |

4tHealth+ is a newer, more capable sibling to 4tHealth and 4tLog, not a replacement for
either. 4tExecutive sits a layer above all three, aggregating their data rather than
duplicating it.

## Stack notes

Built around the Fortinet FortiManager / FortiAnalyzer API, with 4tAnalyst and 4tHealth+
using an LLM via MCP to review and draft rule changes before they ever reach a human
reviewer.

<br/>

<div align="center">
<sub>This is a personal portfolio project — not affiliated with or endorsed by Fortinet.</sub>
</div>
