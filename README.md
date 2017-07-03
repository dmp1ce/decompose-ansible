# Decompose Ansible

Decompose environment for helping to manage and run Ansible playbooks.

## Example

``` sh
mkdir ansible-example && cd ansible-example
decompose --init https://github.com/dmp1ce/decompose-ansible.git

# Create your own Ansible playbooks

decompose --help
decompose run-playbook production-hosts webservers.yml all
```
