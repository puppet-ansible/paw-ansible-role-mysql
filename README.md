# paw_ansible_role_mysql

## Description

This Puppet module was Converted from Ansible role: **ansible_role_mysql**

MySQL server for RHEL/CentOS and Debian/Ubuntu.

## Conversion Details

- **Converted on**: 2025-10-31
- **Original Author**: geerlingguy
- **License**: license (BSD, MIT)

## Usage

Include the module in your Puppet manifest:

```puppet
include paw_ansible_role_mysql
```

Or with custom parameters:

```puppet
class { 'paw_ansible_role_mysql':
  # Add your parameters here
}
```

## Parameters

See `manifests/init.pp` for the full list of available parameters.

## Requirements

- Puppet 6.0 or higher
- puppet_agent_runonce module for task execution
- Ansible installed on target nodes for task execution

## License

license (BSD, MIT)
