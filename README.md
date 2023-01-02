ansible-elk
=========

In this projetcs we automate the installation of a ELK stack using ansible.
The differents components installed are:
* Elasticsearch
* Logstash
* Kibana

Requirements
------------

* ansible version >= 2.9

Role Variables
--------------

[defaults vars path](vars/main.yml)

Dependencies
------------
- **Java**

Example Playbook
----------------

    - hosts: {{ playbook_hosts }}
      roles:
         - ansible-elk

Repository status
-----------------

Development in progress ...

Author
------
* Mansour KA - [email](kamansour06@gmail.com)