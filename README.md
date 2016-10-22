Deploy YOMYPOPCORN with Ansible
===============================

## Example

```sh
ansible-playbook -i production full.yml
```

```sh
ansible-playbook -i staging full.yml
```

## Playbooks

 - `full.yml`: Deploys the entire stack including tools
 - `apps.yml`: Deploys just the YOMYPOPCORN apps and their dependencies
 - `migration-rename.yml`: Renames everything from old names to the new names.
