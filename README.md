# ansible-netapp-cdot
simple raw ssh to create a netapp clustermode SVM with most artifacts with ansible playbook
change the vars.yml to your soecs, and run 'ansible-playbook create.yml' .. or for remove 'ansible-playbook remove.yml'
do not change the ordering in the playbooks, a lot of things have dependencies.
