# Validation Tests (End-to-End)
Status: Draft (to be updated during implementation)

## Goal
Confirm the same test activity appears across:
- Collector (Event Viewer)
- Wazuh
- Elastic
- Splunk

## Test cases to run
- Failed logon / brute force simulation
- Suspicious PowerShell execution
- Basic network connection telemetry (Sysmon Event ID 3)

## Evidence to add
- Screenshot per platform per test case
- Timestamp alignment notes (time sync / timezone)
- Quick “expected vs observed” notes
