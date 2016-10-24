# Ansible-AddRem-Devs
Adding and removing new developers SSH keys

This is a YAML Playbook that allows you to easily add and remove new developer's SSH keys to a Linux server. You would need to edit the "hosts" file to put the names/IPs of the servers you want to control. And then you would run either the Add or Remove playbook. You will be prompted to first enter the name of the user on the server for which you want to add or remove the SSH key from. You would then be prompted for the SSH key. 