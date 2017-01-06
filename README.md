# ansible_identityiq_sandbox
vagrant + ansible scripts for create sandbox with sailpoint identityiq

## required:
virtualbox
vagrant
vagrant-vbguest
identityiq.war v 7.0

## tested only on windows!

## step by step:
1) install latest virtualbox
2) install latest vagrant
3) configure system environment
in cmd:
4) vagrant init centos/7
5) vagrant plugin install vagrant-vbguest
6) clone from git
7) vagrant up

### login list:
system: vagrant or root
tomcat: vagrant
mysql: identityiq or root
identityiq: spadmin

### password everywhere: vagrant 
except:
- in mysql Vagrant_17$
- im iiq admin

## base vagrant image: centos/7
java 8
tomcat 7 (soon to be 8)
mysql 5.7