# centos7-php70-nginx-mariadb-ansible

## Requirements

### Host

* Ansible 1.9

### Client

* CentOS 7
  - The state that initial setting ends in using https://github.com/serima/centos7-initalize-ansible

## Usage

First, you need to edit `hosts`, `group_vars/all`

```
% ansible-playbook -i hosts playbook.yml -vvv
```
