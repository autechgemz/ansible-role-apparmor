# Ansible Role: apparmor

## Description

Manage Application Armor flags

## Requirements

None

## Dependencies

None

## OS Platforms

- Ubuntu

## Example Playbook

```
- hosts: all
  roles:
    - apparmor
```

## Role Variables

### apparmor_package_ensure: (string)

```
apparmor_package_ensure: 'present'
```

### apparmor_service_ensure: (string)

```
apparmor_service_ensure: started
```

### apparmor_service_enable: (bool)

```
apparmor_service_enable: true
```

### apparmor_grub_config: (bool)

```
apparmor_grub_config: false
```

## Example vars

```
apparmor_grub_config: true
```
