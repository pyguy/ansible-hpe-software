HPE Software role
=================

This role is installing the HPE software on different platforms using ansible roles.

It's providing an easy way to install necessary HPE softwares according to the
server baremetal generations and OS.

Tested platforms are:

  * Ubuntu
    * bionic
    * xenial
    * trusty
    * precise


  * Debian
    * stretch
    * jessie
    * squeeze
    * wheezy


  * CentOS 7

links
-----

* [HPE Management Component Pack](https://downloads.linux.hpe.com/SDR/project/mcp/)
* [HPE Repository Listing](http://downloads.linux.hpe.com/SDR/repo/)
* [HPE Project Repositories](https://downloads.linux.hpe.com/SDR/index.html)

Requirements
------------

This role requires [Ansible 2.6.0](https://docs.ansible.com/ansible/devel/roadmap/ROADMAP_2_6.html) or higher.

You can simply use pip to install (and define) a stable version:

```sh
pip install ansible==2.6.3
```

Install role
------------
```sh
ansible-galaxy install pyguy.hpe_software
```
