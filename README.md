# Practice
Ansible Practice Playbooks
This repository will provide you scenarios to practice writing playbooks from very basics.
Scenario_1:

Task 1:
Create & Setup 3 Host Systems, Make Sure that Open SSH Server is installed on all the systems including the Control and Host nodes.

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
