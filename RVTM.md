# 🧩 Requirements Verification Traceability Matrix (RVTM)

| Status | Requirement Description | Test |
|--------|--------------------------|-----|
| [ ] | Redundant AD infrastructure using DC1 + DC2. One should be able to turn off DC1 or DC2 and still manage AD & log in via W1, W2, MGMT1.| Video |
| [x] | DHCP1 and DHCP2 provide redundant DHCP to LAN. Test with ipconfig /release & /renew from W1 after turning off either server. | Video |
| [ ]| MGMT2 as Ansible controller for all systems except workstations & firewall. Run interactive commands. | Video |
| [ ] | Deploy a new app to Util using Ansible (not covered in class). | Video |
| [x] | AD Infrastructure: MGMT1, DC1, DC2, DFS1, DFS2, W1, W2 must join groupname.local domain. At least one Linux system joined. | Video |
| [ ] | Create AD group `linux-admins`; group members can sudo to root on a Linux system. | Video |
| [x]| Install Docker and a non-WordPress app (e.g. wiki) on it. |  [Video](https://drive.google.com/file/d/1IslR3kWc0vkMdkBDQlQ4uQnRg8kViWHg/view?usp=sharing) |
| [ ] | Create Domain GPO: allow RDP between W1 and W2. | Video |
| [ ] | GPO for corporate wallpaper on W1, W2, MGMT1. | Video |
| [ ] | GPO to move W1 and W2 profiles/home to DFS share. | Video |
| [ ] | Use Ansible to install an `apt` package. | Video |
| [ ] | Use Ansible to install a `yum` package. | Video |
| [ ] | Use Ansible to add a new Linux local user. | Video |
| [ ] | Use Ansible to add a new Windows domain user. | Video |
