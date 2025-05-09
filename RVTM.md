# 🧩 Requirements Verification Traceability Matrix (RVTM)

| Status | Requirement Description | Test |
|--------|--------------------------|-----|
| [x] | Redundant AD infrastructure using DC1 + DC2. One should be able to turn off DC1 or DC2 and still manage AD & log in via W1, W2, MGMT1.| [Video](https://drive.google.com/file/d/1PWz-g6RFrRcl0zI79sNpKHcLhHwJL3M7/view?usp=drive_link) |
| [x] | DHCP1 and DHCP2 provide redundant DHCP to LAN. Test with ipconfig /release & /renew from W1 after turning off either server. | [Video](https://drive.google.com/file/d/1M686qNo_CgllN9P6sFQOfMMjIk6t_uUH/view?usp=drive_link) |
| [X]| MGMT2 as Ansible controller for all systems except workstations & firewall. Run interactive commands. | [Video](https://drive.google.com/file/d/1D4mQTwzcNBHQmS8cllgjLwFTWhahY4sM/view?usp=sharing) |
| [x] | Deploy a new app to Util using Ansible (not covered in class). | [Video](https://drive.google.com/file/d/1JeC6UQ6-x5AxZO9ihbVh9ZulLWG8RLda/view?usp=sharing) |
| [x] | AD Infrastructure: MGMT1, DC1, DC2, DFS1, DFS2, W1, W2 must join groupname.local domain. At least one Linux system joined. | [Video](https://drive.google.com/file/d/1M6U0JPlu7IlHePfSOTGVKmZ6B6fjB0DB/view?usp=drive_link) |
| [X] | Create AD group `linux-admins`; group members can sudo to root on a Linux system. | [Video](https://drive.google.com/file/d/143g130O0I0lBH_eZ0P8lujuFNugCyHes/view?usp=sharing) |
| [x]| Install Docker and a non-WordPress app (e.g. wiki) on it. |  [Video](https://drive.google.com/file/d/1IslR3kWc0vkMdkBDQlQ4uQnRg8kViWHg/view?usp=sharing) |
| [x] | Create Domain GPO: allow RDP between W1 and W2. | [Video](https://drive.google.com/file/d/1geIKM_ehYXuaIPcbIDeUMS_LwtWndRd2/view?usp=sharing) |
| [X] | GPO for corporate wallpaper on W1, W2, MGMT1. |  [Video](https://drive.google.com/file/d/1lzMmfWHb_1rbvnUB9v1qaY-ZcpQ9vAj1/view?usp=sharing) |
| [X] | GPO to move W1 and W2 profiles/home to DFS share. | [Video](https://drive.google.com/file/d/13MLlGqyOHlCc15w0hl_mFYLzndz3VjLQ/view?usp=sharing) |
| [X] | Use Ansible to install an `apt` package. | [Video](https://drive.google.com/file/d/1GdT-eVRAHs4K8lNBUlNevfm0HUakgkA6/view?usp=sharing) |
| [X] | Use Ansible to install a `yum` package. | [Video](https://drive.google.com/file/d/1JLEVdfd6vXQ6ft9Bq8yiJcIL5Gc15C_r/view?usp=sharing) |
| [X] | Use Ansible to add a new Linux local user. | [Video](https://drive.google.com/file/d/1d3Qh9lQvrMxb_pRCFL9MN9LmFtyM6ArO/view?usp=sharing) |
| [x] | Use Ansible to add a new Windows domain user. | [Video](https://drive.google.com/file/d/1QgVBlr30mTOAaFpeeIZ4iJDaTvvfFi_k/view?usp=sharing) |


[Final Video](https://drive.google.com/file/d/1mNnIQrgWMuFU9gTkuLq_cDojjk9rtYwY/view?usp=sharing)
