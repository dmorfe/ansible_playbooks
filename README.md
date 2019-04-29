# ansible_playbooks
Ansible Playbooks

# These playbooks are for the creation and deployment of current user SSH ID into linux hosts so you can run playbooks against these servers without having to enter your user/pass. There are few other playbooks to update servers.

They can be call individually or exceute all at once by running the push_ssh_id.yml playbook.

When pushing the SSH ID to the servers for the first time you have to specify --ask-pass option to ask for current user password. This user need to have login access to the servers to which the SSH ID are being pushed.

Once the SSH ID have being pushed the user on the control machine won't have to enter the password any longer as long as the ID is not removed from the servers.
