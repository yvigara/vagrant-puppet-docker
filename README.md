Centos 7 - Vagrant - Docker - Puppet
====================================

An example of how to use puppet to automate the deployment of a Nginx Docker image on top of a fresh Centos 7 vagrant image.

Prerequisites:
-------------

git, vagrant and virtualbox installed

Usage:
-----

* Clone the repo

* Start the docker1 vagrant box:

    vagrant up docker1

* Browse: http://192.168.56.2:9000
  You should see "Welcome on docker1"

* You can ssh to the box using:

    vagrant ssh docker1
  or
    ssh vagrant@192.168.56.2 # password: vagrant
