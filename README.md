ispconfig-migrate
=================

Ansible script to move the ispconfig installation on one machine to another machine.
Written for ubuntu, dovecot, postfix, nginx

It will create a backup of the source server of the following elements: 
* Ispconfig database 
* all the mail in /var/vmail

_Not yet in here_
* a copy of the nginx available and enabled sites
* transferring it to another machine

