Ansible Freifunk Regensburg
===========================

## Requirements

The python package netaddr is required on the host running ansible.
The vault password must be stored in `.vault_pass`.


## Running Ansible

To deploy all defined roles on all servers simply run `ansible-playbook site.yml`.
To deploy only one server run `ansible-playbook -i "hostname," site.yml`.


## Notes

Some roles are derived from https://github.com/FreifunkBremen/ansible/
