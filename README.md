# Practice
Ansible Practice Playbooks
This repository will provide you scenarios to practice writing playbooks from very basics.

Scenario_1:

Task 1:
Create & Setup 3 Host Systems, Make Sure that Open SSH Server is installed on all the systems including the Control and Host nodes.

Once the Hosts are ready, make sure all the server is configured in such a way that the playbook can install the softwares into the hosts. This can be done by giving the User the required privileges or making changes in the system configuration.

Options to do that are:

1. Make the User as Root User (https://linoxide.com/usr-mgmt/give-normal-user-root-privileges/?unapproved=8726&moderation-hash=28cfa559da5b63f10b4c0f4a9893939b#comment-8726)
2. Update the sshd_config file. This will allow Root permit. (https://www.liquidweb.com/kb/enable-root-login-via-ssh/)

Write one inventory file with all the 3 host details

Write 3 playbooks
1. python-install.yml

Task 1: Install python
Dependencies:
python-setuptools
python-dev
build-essential
python-pip
python3-pip
python-mysqldb
				
Task 2: Install Python Flask
Dependencies:
flask
flask-mysql
		
2. mysqldb.yml

Task 1: Install Mysql
mysql-server
mysql-client
	
Task 2: Start Service
mysql

3. docker-install.yml

Task 1: Install Docker
