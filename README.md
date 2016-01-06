# openstack-ansible
* Ansible playbooks for OpenStack kilo.
* This is for all-in-one provisioning.

## Provision

### Prerequisites:

* Ansible >= 1.6.0
* Ubuntu  >= 14.04

`pip install ansible`

`git clone https://github.com/chiisaihayashi/ansible-openstack-aio`

### Usage:

change variables in "group_vars/all", "common/templates/hosts"


run `ansible-play-book -i hosts site.yml`

* Once deployment is up and running, you can visit the dashboard by visit http://{{ controller ip }}/horizon in the browser.

* You can also "source /opt/admin-openrc.sh"; then you are able to run openstack command lines.


### References:

* https://github.com/kidchang/openstack-ansible

* http://docs.openstack.org/kilo/install-guide/install/apt/content/

