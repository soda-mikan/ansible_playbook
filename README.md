# ansible_playbook

ansible_rsynclsync/
ansible_rsynclsync/inventory/
ansible_rsynclsync/inventory/hosts
ansible_rsynclsync/book/
ansible_rsynclsync/book/yum_install.yml
ansible_rsynclsync/book/mod_security_install.yml
ansible_rsynclsync/book/tomcat_install.yml
ansible_rsynclsync/book/rsync_lsync.yml
ansible_rsynclsync/files/
ansible_rsynclsync/files/tomcat.service
ansible_rsynclsync/files/lsyncd.conf_2
ansible_rsynclsync/files/lsyncd.conf_1
ansible_rsynclsync/files/rsyncd.conf

# lsyncd --version
Version: 2.2.2

# rsync --version
rsync  version 3.0.9  protocol version 30

# cat /etc/redhat-release
CentOS Linux release 7.4.1708 (Core)

ansible-playbook -i ansible_rsynclsync/inventory/hosts ansible_rsynclsync/book/rsync_lsync.yml

