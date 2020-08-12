## Welcome

To install epel-repo and ansible code written in bash

```
bash install_ansible.sh
```

### Check connectivity

```bash
ansible all -m ping -u cloud_user -k -K
```
It will propmt for login & sudo passwords.

### Install Docker in CentOS

To execute the ansible playbook for installing docker in the centos machine

```
ansible-playbook install-docker.yaml -u cloud_user -k -K
```

