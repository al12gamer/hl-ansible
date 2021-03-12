# Installs-Ansible
ansible scripts used for [s31bz-postinstall](https://github.com/al12gamer/s31bz-postinstall) script
This is forked from Joey's work on scripts, work in progress btw


## Setup:
* Edit `/etc/ansible/ansible.cfg` to set the `roles_path`


## Example:
You can run a playbook by using the following command from the `playbooks` dir:
``` shell
ansible-playbook nginx.yml --limit localhost
```
