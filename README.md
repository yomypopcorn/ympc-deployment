Deploy YOMYPOPCORN with Ansible
===============================

## Example

```sh
ansible-playbook -e YO_APIKEY='yo-api-key-blablab-labl-ablablablabl' full.yml
```

## Playbooks

 - `full.yml`: Deploys the entire stack including tools
 - `apps.yml`: Deploys just the YOMYPOPCORN apps and their dependencies
