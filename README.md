   # SOC Lab
   A small security operations lab I am building step by step.

   ## Status
   - [x] Stage 0: Ubuntu Server 24.04.5 VM (wazuh-server) created, snapshot "clean-install" saved
   - [x] Stage 1 complete: Wazuh installed and secured (admin password changed, package repo disabled); local monitoring on wazuh-server confirmed working via SC-001 (SSH login as a non-existent user, rule 5710, investigated); five artifact templates written.
   - [x] Stage 2 in progress: Windows Server 2022 VM (win-client) created; host-only network (192.168.56.0/24) set up between both VMs; Wazuh agent installed on win-client and successfully enrolled (status: Active). Still to do: install Sysmon, run and detect a first Windows scenario.
