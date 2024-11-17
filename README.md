# sshd [![Ansible Role](https://img.shields.io/ansible/role/d/cornfeedhobo/sshd)](https://galaxy.ansible.com/cornfeedhobo/sshd)

Install and configure sshd

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [sshd_bin_path](#sshd_bin_path)
  - [sshd_config_contents](#sshd_config_contents)
  - [sshd_config_file_name](#sshd_config_file_name)
  - [sshd_configure](#sshd_configure)
  - [sshd_group](#sshd_group)
  - [sshd_install](#sshd_install)
  - [sshd_owner](#sshd_owner)
  - [sshd_package_state](#sshd_package_state)
  - [sshd_packages](#sshd_packages)
  - [sshd_service](#sshd_service)
  - [sshd_service_enabled](#sshd_service_enabled)
  - [sshd_service_name](#sshd_service_name)
  - [sshd_service_state](#sshd_service_state)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.9`

## Default Variables

### sshd_bin_path

#### Default value

```YAML
sshd_bin_path: '{{ __sshd_bin_path }}'
```

### sshd_config_contents

#### Default value

```YAML
sshd_config_contents: ''
```

### sshd_config_file_name

#### Default value

```YAML
sshd_config_file_name: ansible-managed
```

### sshd_configure

#### Default value

```YAML
sshd_configure: false
```

### sshd_group

#### Default value

```YAML
sshd_group: root
```

### sshd_install

#### Default value

```YAML
sshd_install: false
```

### sshd_owner

#### Default value

```YAML
sshd_owner: root
```

### sshd_package_state

#### Default value

```YAML
sshd_package_state: present
```

### sshd_packages

#### Default value

```YAML
sshd_packages: '{{ __sshd_packages }}'
```

### sshd_service

#### Default value

```YAML
sshd_service: false
```

### sshd_service_enabled

#### Default value

```YAML
sshd_service_enabled: true
```

### sshd_service_name

#### Default value

```YAML
sshd_service_name: '{{ __sshd_service_name }}'
```

### sshd_service_state

#### Default value

```YAML
sshd_service_state: started
```

## Discovered Tags

**_sshd_**

**_sshd-configure_**

**_sshd-install_**

**_sshd-service_**


## Dependencies

None.

## License

MIT

## Author

cornfeedhobo
