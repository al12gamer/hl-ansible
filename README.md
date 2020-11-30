# hl-ansible
ansible scripts used for homelab


## Setup:
* Edit `/etc/ansible/ansible.cfg` to set the `roles_path`


## Example:
You can run a playbook by using the following command from the `playbooks` dir:
``` shell
ansible-playbook nginx.yml --limit localhost
```
