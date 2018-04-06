# ansible-role-jenkins

Tested on Ansible 2.4.2 and Ubuntu 16.04

## Playbook sample
This playbook installs jenkins and openjdk 8.
```yaml
- hosts: jenkins_host
  become: yes
  roles:
    - jenkins
```
