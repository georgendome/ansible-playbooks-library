# Ansible Playbooks Library

A collection of Ansible playbooks used for server provisioning, patching, hardening, user management, and configuration automation across Linux and Windows environments.

## Features
- Automated Linux server builds (Ubuntu, CentOS)
- Windows Server configuration and patching
- Active Directory user/group automation
- CIS benchmark hardening tasks
- Package installation and service configuration
- Log rotation and monitoring agent deployment

## Technologies
- Ansible
- YAML
- Linux (Ubuntu, CentOS)
- Windows Server
- Active Directory
- VMware / Cloud VMs

## Structure
playbooks/
  ├── linux_provision.yml
  ├── windows_patching.yml
  ├── ad_user_create.yml
  ├── cis_hardening.yml
  ├── install_monitoring_agent.yml
