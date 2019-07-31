# Ansible-basics
This GIT Repo includes some basic Ansible Playbooks which is used in day to day work

<b>1) createuser.yml - </b>This playbook can be used to create user on all linux hosts with complete sudo or admin access. We need to provide host group of linux machines and user name & password which need to be set on all machines in this playbook.

<b>2) removeuser.yml - </b>This playbook can be used to remove user on all linux hosts. We need to provide user name which needs to be removed and also the host group of linux machines need to be mentioned in the playbook.

<b>3) selinux_disable.yml - </b>This playbook can be used to disable selinux on all linux hosts and restarts the host machine after disabling selinux. Please note: it will not restart host machine if selinux is already disabled. We need to mention the host group of linux machines in the playbook.

<b>4) archive.yml - </b>This playbook creates the zip archive of the files having particular pattern name in the target directory. We need to provide host group name of the linux machines in the playbook. We also need to provide the directory path from where the files will get archived ( like /home/target/ ) and also the pattern name of the files ( like file1-* ). Also final path & name of the archive file needs to be mentioned.

<b>5) ssh-root-disable.yml - </b>This playbook can be used to disable root login via ssh on all linux host machines mentioned in host group. We just need to provide the host group of linux machines in the playbook.
