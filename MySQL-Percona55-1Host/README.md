Simple MySQL testbox with

* Percona-server 5.5
* Percona-Toolkit
* SysBench 0.5
* sbtest.sh (/usr/local/bin/sbtest.sh - preconfigured sysbench test script)

What you need
==============
  - Vagrant
  - Ansible 

## Installation


```
git clone https://github.com/mszel-blackbirdit/vagrant
cd vagrant/MySQL-Percona55-1Host/
vagrant up
vagrant ssh
```

## Port redirections:
```
testbox:22 -> localhost:2242
testbox:3306 -> localhost: 3342
```
