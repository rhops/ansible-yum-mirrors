An Ansible role to configure CentOS yum mirrors for [base](http://mirror.centos.org/centos/) and [EPEL](http://download.fedoraproject.org/pub/epel).

### Dependencies
None

### Tested Environment
* Ansible 2.1
* CentOS 6/7

### Installation
```
ansible-galaxy install rhops.yum-mirrors
```

### Role Variables
* Configure base repo

```
yum_mirrors_base: https://mirrors.tuna.tsinghua.edu.cn/centos
```

* EPEL must be installed before using EPEL mirror because it is not available by default.

```
yum_mirrors_epel_enabled: yes
yum_mirrors_epel: https://mirrors.tuna.tsinghua.edu.cn/epel
```

### License
Apache 2.0

### Author Information

This role was created in 2017 by [Jeff Li](http://blog.jeffli.me)

