# config-workstation

This repository contains an Ansible playbook used to set up a workstation with main tools for daily use.

This playbook was tested in Linux Mint 19.0 (Ubuntu Bionic based).

1. Go to your user's directory:

```console
$ cd ~/
```

2. Update and install Ansible:

```console
$ sudo apt update && sudo apt install ansible unzip git
```

3. Clone repository:

```console
git clone https://github.com/JubittLinux/config-workstation.git
```

4. Apply:

```console
ansible-playbook tools/workstation.yml --ask-become-pass
```
