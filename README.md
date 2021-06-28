Role Name : kube_master
=========

Configure Kubernetes Master node

Requirements
------------
none

Role Variables
--------------

packages: 
  - docker 
  - kubelet
  - kubectl
  - kubeadm
  - iproute-tc

services:
  - docker
  - kubelet

Dependencies
------------
none

Example Playbook
----------------

Playbook for kubernetes_master
    - hosts: tag_Name_of_managed_node
      roles:
         - kubernetes_master

License
-------

BSD

Author Information
------------------

https://www.linkedin.com/in/ajeetrai266