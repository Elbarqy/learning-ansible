- ansible-playbook let us place Ansible configuration into files so we can reliable run the same set of commands over and over again
- we create a list of systems that ansible can iterate over.. these are stored in an inventory. /etc/ansible-hosts by default


### one important configuration to consuder before running ansible 

- Authorized-keys in the server side to allow ansible connection
- Sudores to allow ansible to have root permissions