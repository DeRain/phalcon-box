# Phalcon box
This [Vagrant](https://www.vagrantup.com/) box helps to buld environment for [Phalcon](https://github.com/phalcon/cphalcon) projects. 
Using [Ansible](https://github.com/ansible/ansible) as provision manager.
Inspired by this [tutorial](https://github.com/hollodotme/Helpers/blob/master/Tutorials/vagrant/self-hosted-vagrant-boxes-with-versioning.md).

## Server stuff ##
- Ubuntu 14.04 LTS (Trusty Tahr)
- nginx
- php-fpm
- cURL
- git
- Node.js
  
## PHP Stuff ##
- PHP 5.6
- Phalcon 2.0.*
- Mcrypt
- GD and Imagick
    
## Node Stuff ##
- NPM
- Bower
- Grunt
- Gulp

## Vagrant Provision Stuff ##
- Ansible

# Notes #
- This box is not including any database. You can add this with ansible roles ([MySQL](https://github.com/geerlingguy/ansible-role-mysql), [MongoDB](https://github.com/UnderGreen/ansible-role-mongodb), etc.)