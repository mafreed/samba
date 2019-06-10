# Install Samba AD - DC  in Ubuntu Server

* Install ansible 
* Update the hosts file with ssh user and pem file location used to ssh
* update the variables required for samba ad-dc to work in 'roles/mysamba/defaults/main.yml' file
* Run the ansible playbook using the below command

# ansible-playbook -i hosts main.yml --ask-sudo-pass
