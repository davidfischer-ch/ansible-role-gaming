# Ansible Role Gaming

Library of Ansible plugins and roles for deploying various services.
See [ansible-roles](https://github.com/davidfischer-ch/ansible-roles) for additional documentation.

This repository hosts the role Gaming and may depend of other roles and plugins of the library.

## Dependencies

This role has no requirements.

## Variables

| Variable | Default | Description |
|---|---|---|
| `gaming_packages` | `[steam-installer]` | Apt packages to install. |
| `gaming_snap_flush_packages` | `{{ gaming_packages }}` | Snap package names to remove before apt install when `desktop_snap_mode` is `partial` or `disabled`. Names must match snap identifiers (may differ from apt names, e.g. `steam` not `steam-installer`). Failures are silenced. |

## License

See [LICENSE.rst](LICENSE.rst).

## Authors

See [AUTHORS](AUTHORS).

2014-2022 - David Fischer
