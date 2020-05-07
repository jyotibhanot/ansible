aws-ssm-agent
=========

This role provide a compliance for install amazon-ssm on your target host.

Example Playbook
----------------

This is a sample playbook file for deploying the aws-ssm-agent
role in a localhost and installing latest amazon-ssm version.

```yaml
---
- hosts: localhost
  become: true
  roles:
    - role: aws-ssm-agent
```

Author Information
------------------

jyoti.bhanot30@gmail.com
