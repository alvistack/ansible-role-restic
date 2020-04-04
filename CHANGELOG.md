# Ansible Role for restic

## 4.3.0 - TBC

### Major Changes

  - Upgrade minimal Molecule support to 3.0.2
  - Migrate role name to lowercase or underline
  - Migrate group name to lowercase or underline
  - Migrate molecule `group_vars` to file
  - Consolidate molecule tests into `default` (noop)
  - Support CentOS 8
  - Download archives to `{{ ansible_user_dir }}/.ansible/tmp`

## 4.2.0 - 2020-02-13

### Major Changes

  - Migrate molecule driver to Libvirt
  - Migrate molecule verifier to Ansible
  - Support Ubuntu 19.10

## 4.1.0 - 2020-01-28

  - Ininitial release for Ansible 2.9 or higher
  - Support both Ubuntu 16.04/18.04 or RHEL/CentOS 7 or openSUSE Leap 15.1
