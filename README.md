# ansible-netapp-cdot

simple raw ssh to create a netapp clustermode SVM with most artifacts with ansible playbook
change the vars.yml to your specifics, and run 'ansible-playbook create.yml' .. or for remove 'ansible-playbook remove.yml'
do not change the ordering in the playbooks, a lot of things have dependencies.

Tested on NetApp Release 8.3.1P2: Wed Dec 09 03:10:24 UTC 2015
