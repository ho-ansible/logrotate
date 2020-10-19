# Ansible role: logrotate
Compress and archive old system logs.

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `logrotate_clear`: list of package-supplied logrotate config to delete

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run before removing config from inventory.

## Dependencies
None.

## License
+ Ansible role licensed [MIT](LICENSE)

## Author Information
+ Ansible role by [Sean Ho](https://github.com/ho-ansible/)
