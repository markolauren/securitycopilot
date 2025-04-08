## Microsoft Security Copilot

This repo contains some of my projects with Security Copilot.

### API plugin for VirusTotal (ip, domain, url)
https://github.com/markolauren/securitycopilot/blob/main/API-GetVirusTotalReport.yaml
<br><br>
_(original by SCStelz here: https://github.com/SCStelz/CopilotForSecurity/tree/main/CustomPlugIns/API-GetVirusTotalIP)_
<br><br>

### SecurityCopilot-Sentinel-Incident-Investigation
My fork of Sentinel Logic App to automate incident entity investigation, summarization & impact analysis using Security Copilot.<br>
The summarization part assumes you've onboarded Sentinel workspace to Unified SecOps platform.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmarkolauren%2Fsecuritycopilot%2Frefs%2Fheads%2Fmain%2FSecurityCopilot-Sentinel-Incident-Investigation_marko.json" target="_blank">
<img src="https://aka.ms/deploytoazurebutton"/>
</a>
<br><br>

2x API connections needs
1) Sentinel conncetor using managed identity, add "Sentinel Responder" role under Identity.
2) Copilot connector needs Authorize under API connections.
<br>

_(original: https://github.com/Azure/Security-Copilot/tree/main/Logic%20Apps/SecurityCopilot-Sentinel-Incident-Investigation, then forked from this: https://github.com/stefanpems/cfs/tree/main/SecurityCopilot-Sentinel-Incident-Investigation)_



