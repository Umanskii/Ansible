Instructions

1.brew install ansible 

2.sudo mkdir /etc/ansible 

3.sudo chown -R your_username:staff /etc/ansible

4. download ansible config file from repo ansible.cfg

5. put ansible.cfg into /etc/ansible

6. mkdir -p ~/tntk_projects/ansible

7. create the following directories under ~/tntk_projects/ansible

 mkdir -p ~/tntk_projects/ansible/roles ~/tntk_projects/ansible/playbooks ~/tntk_projects/ansible/inventory

8. download hosts file from repo 

9. put the host file below under ~/tntk_projects/ansible/inventory 

10 . setup passwordless ssh between your local machine and your EC2 instances. Refer to this doc SSH key-pair setup  
