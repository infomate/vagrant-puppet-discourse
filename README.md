# Discourse Installation Using Vagrant and puppet 

Discourse-Discourse is the 100% open source discussion platform built for the next decade of the Internet. It works as: a mailing list. a discussion forum.


# Installation
Tested on an Intel i3, 3GB RAM, 500GB HD
Ubuntu Trusty 32bit
* VirtualBox 4.3.10_Ubuntur93012
* Vagrant 1.7.4
* Puppet 4.2.2

# Dependencies 
Already taken care-of via vagrant_provision.sh
* puppetlabs-ruby
* dwerder-redis
* jfryman-nginx
* puppetlabs-postgresql

Required by main modules (from puppetforge)
* puppetlabs/stdlib
* puppetlabs/apt
* puppetlabs/concat
* stahnma/epel
* puppetlabs-vcsrepo
* garethr-docker

# Linux / Ubuntu
 1. git clone https://github.com/infomate/vagrant-puppet-discourse.git [dev_folder]
 2. cd [dev_folder]
 3. vagrant up
 4. from any browser:
    http:[your_host_machine_IPAdd]:8080
