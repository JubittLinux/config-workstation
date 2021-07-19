# config-workstation

This repository contain an Ansible playbook used to set up a workstation with main tools for daily use.

This Ansible playbook was tested in Linux Mint 19.0 (Ubuntu Bionic based).

1. Update and install Ansible:

$ sudo apt update && sudo apt install ansible unzip git

2. Clone repository:

$ git clone https://github.com/JubittLinux/config-workstation.git

3. Apply:

$ ansible-playbook tools/workstation.yml --ask-become-pass
