# SOC Lab
A small security operations lab I am building step by step.

## Status
- [x] Stage 0: Ubuntu Server 24.04.5 VM (wazuh-server) created, snapshot "clean-install" saved
- [x] Stage 1 complete: Wazuh installed and secured (admin password changed, package repo disabled); local monitoring on wazuh-server confirmed working via SC-001 (SSH login as a non-existent user, rule 5710, investigated); five artifact templates written.
- [x] Stage 2 complete: Windows Server 2022 VM (win-client) created; host-only network (192.168.56.0/24) between both VMs; Wazuh agent Active; VirtualBox Guest Additions installed; Sysmon v15.22 installed with the Neo23x0 config; Sysmon-to-Wazuh integration confirmed working after diagnosing and fixing a malformed channel path (INV-002); first Windows scenario (SC-002, base64-encoded PowerShell, T1059.001) detected and investigated (INV-003, rule 92057, level 12). Stage 3 (more scenarios and custom detections) next.
