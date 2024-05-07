Template to Configure 2fa IBM Solution - ISV 
=========

This template include a role to install and configure IBM Security Verify Gateway for Linux PAM (Pluggable Authentication Modules). 

Requirements
------------

This template need to be run into AAP Application and will execute a role to Install and Configure IBM Security Verify Gateway for Linux PAM (Pluggable Authentication Modules).

Role Variables
--------------

This template has two variables that is part of isv-linux-role that can be found in the below link:
https://github.ibm.com/SreDistributedBrazilS1/isv-linux-role/

Usage Playbook
----------------

Login into AAP Application and open [automation](https://cio-ansible-automation.ibm.com/#/templates/job_template/4631/details)

Click on launch button :arrow_down:
![launch](https://github.ibm.com/SreDistributedBrazilS1/install-isv-linux/tree/main/images/image1.jpg)

Select Inventory to run:
![launch](https://github.ibm.com/SreDistributedBrazilS1/install-isv-linux/tree/main/images/image2.jpg)

Select Credential:
![launch](https://github.ibm.com/SreDistributedBrazilS1/install-isv-linux/tree/main/images/image3.jpg)

Select Limit Server if necessary:
![launch](https://github.ibm.com/SreDistributedBrazilS1/install-isv-linux/tree/main/images/image4.jpg)

Fill the Survey:
![launch](https://github.ibm.com/SreDistributedBrazilS1/install-isv-linux/tree/main/images/image5.jpg)

Client ID: This Variable can be found in 2faa Portal 
(https://ibm-2faaas-srp.prod.identity-services.intranet.ibm.com)

OBF Client Secret: This Variable can be found in 2faa Portal 
(https://ibm-2faaas-srp.prod.identity-services.intranet.ibm.com)

**Click on Rotate Button on 2fa Portal (example below)
![launch](https://github.ibm.com/SreDistributedBrazilS1/install-isv-linux/tree/main/images/image6.jpg)

Last step, Launch this template and wait to finish. 

Validate the access in the server and check if w3id Multifactor will prompt in SSH Session. 
![launch](https://github.ibm.com/SreDistributedBrazilS1/install-isv-linux/tree/main/images/image7.jpg)

Author Information
------------------

Created by Bruno Santinato

CIO Hybrid Cloud – SRE 

Squad: SRE_Distributed_Brazil_S1

Email : bruno.santinato@ibm.com
