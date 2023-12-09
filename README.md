## Introduction
For GIT (Github) testing only! Ansible playbooks for setup OpenVPN server.
## Current Releases
0.1 - Initial Commit; <br />
## Platforms
Tested with Debian 9, 10, 11, 12, Ubuntu Server 18,20, 22, CentOS 7, 8, CentOS Stream 9 
## Usage
Typical usage:
> ansible-playbook -i vpn.yml

Usage playbook for adding new OpenVPN user and certificate:
> ansible-playbook -i vpn.yml --ask-vault-pass

See using notices in playbooks
## Licenses
Use and modify on your own risk.
