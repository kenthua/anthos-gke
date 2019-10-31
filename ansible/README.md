# Ansible Playbooks

## Generate static hosts
Requires python module `netaddr` for IP calculation.

```shell
pip install netaddr
```

Edit the main.yaml with desired variable values.
The resulting file will be a generated cluster-host.yaml

```shell
ansible-playbook main.yaml
```




