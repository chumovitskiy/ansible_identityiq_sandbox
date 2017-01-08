# ansible_identityiq_sandbox
vagrant + ansible scripts for create sandbox with sailpoint identityiq

## required:
- virtualbox
- vagrant
- vagrant-vbguest
- identityiq.war v 7.0

## tested only on windows!

## step by step:
- install latest virtualbox
- install latest vagrant
- configure system environment
- (in cmd) vagrant init centos/7
- (in cmd) vagrant plugin install vagrant-vbguest
- clone from git
- (in cmd) vagrant up

### login list:
- system: vagrant or root
- tomcat: vagrant
- mysql: identityiq or root
- identityiq: spadmin

### password everywhere: vagrant 
except:
- in mysql Vagrant_17$
- im iiq admin

## base vagrant image: centos/7
- java 8
- tomcat 7 (soon to be 8)
- mysql 5.7

# TODO:

## tomcat
- upgrade to ver. 8
- change file to template

## identityIQ
- change file to template
- iiq import\expot in iiq