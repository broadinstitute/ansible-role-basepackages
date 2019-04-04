# ansible-role-basepackages

#### Overview
This role will install yum packages from the packages var.

#### Variable
```
---
packages:
  - jq
  - bind-utils
  - git
  - htop
  - python36
  - python36-pip
```

#### Samaple playbook
```
---
- hosts: localhost
  roles:
  - role: ansible-role-basepackages
  ```
