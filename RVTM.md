# 🧩 Requirements Verification Traceability Matrix (RVTM)

| Req ID | Requirement Description | Verification Method | Test Case ID | Status | Notes |
|--------|--------------------------|----------------------|--------------|--------|-------|
| RQ-001 | Redundant AD infrastructure using DC1 + DC2. One should be able to turn off DC1 or DC2 and still manage AD & log in via W1, W2, MGMT1. | Functional Test (Failover) | TC-001 | ⬜ Not Verified | Simulate failover & test login |
| RQ-002 | DHCP1 and DHCP2 provide redundant DHCP to LAN. Test with ipconfig /release & /renew from W1 after turning off either server. | Functional Test | TC-002 | ⬜ Not Verified | |
| RQ-003 | MGMT2 as Ansible controller for all systems except workstations & firewall. Run interactive commands. | Demonstration, Script Execution | TC-003 | ⬜ Not Verified | |
| RQ-004 | Deploy a new app to Util using Ansible (not covered in class). | Ansible Playbook Execution | TC-004 | ⬜ Not Verified | App must be new & provisioned via playbook |
| RQ-005 | AD Infrastructure: MGMT1, DC1, DC2, DFS1, DFS2, W1, W2 must join groupname.local domain. At least one Linux system joined. | Inspection, Join Test | TC-005 | ⬜ Not Verified | Use `realm list` or `domainjoin-cli` on Linux |
| RQ-006 | Create AD group `linux-admins`; group members can sudo to root on a Linux system. | Functional Test | TC-006 | ⬜ Not Verified | Check `/etc/sudoers` or group binding |
| RQ-007 | Install Docker and a non-WordPress app (e.g. wiki) on it. | Deployment Test | TC-007 | ⬜ Not Verified | Use `docker ps` to confirm |
| RQ-008 | Create Domain GPO: allow RDP between W1 and W2. | GPO Application Test | TC-008 | ⬜ Not Verified | Test RDP login from W1 ↔ W2 |
| RQ-009 | GPO for corporate wallpaper on W1, W2, MGMT1. | Visual Inspection | TC-009 | ⬜ Not Verified | Confirm wallpaper set |
| RQ-010 | GPO to move W1 and W2 profiles/home to DFS share. | File System Inspection, Login Test | TC-010 | ⬜ Not Verified | Check redirected folders |
| RQ-011 | Use Ansible to install an `apt` package. | Playbook Execution | TC-011 | ⬜ Not Verified | Example: `ansible -m apt` |
| RQ-012 | Use Ansible to install a `yum` package. | Playbook Execution | TC-012 | ⬜ Not Verified | Example: `ansible -m yum` |
| RQ-013 | Use Ansible to add a new Linux local user. | Playbook Execution | TC-013 | ⬜ Not Verified | Confirm with `id` or `getent passwd` |
| RQ-014 | Use Ansible to add a new Windows domain user. | Playbook Execution | TC-014 | ⬜ Not Verified | Confirm via ADUC or PowerShell |
