# Diagrams
Status: Draft (to be updated during implementation)

## TODO: pipeline-diagram.png (Checklist)
Create and upload: `pipeline-diagram.png`

Include (high-level only):
- [ ] Endpoints: AD-WIN10, AD-WIN11
- [ ] Telemetry sources: Windows Security + Sysmon
- [ ] Transport: WEF (source-initiated subscription) → Collector (AD-DC01 or WEC01)
- [ ] Downstream platforms: Wazuh, Elastic, Splunk Free
- [ ] Arrow labels showing flow direction (Endpoints → Collector → Platforms)

Do NOT include:
- [ ] WAN/public IPs, domains/DDNS, VPN endpoints/keys
- [ ] Port forwards, exposed services, credentials/secrets

Optional:
- [ ] Upload editable source file too (e.g., `pipeline-diagram.drawio`)
