

# Udacity Linux Server Configuration Project
* Goal - You will take a baseline installation of a Linux distribution on a virtual machine and prepare it to host your web applications, to include installing updates, securing it from a number of attack vectors and installing/configuring web and database servers.

# IP and URL
* IP Address: 18.188.76.124
* Hostname: http://ec2-18-188-76-124.us-east-2.compute.amazonaws.com/
* Passphrase for grader key : "udacity"
* SSH port: 2200

# Summary of Software Installed
* Apache2
* PostgreSQL
* GIT
* mod_wsgi
* Python
* virtualenv
* Flask
* httplib2
* sqlalchemy
* psycopg2
* sqlalchemy_utils
* requests

# Configurations Made
* Add user grader
* Add user grader to sudo group
* Update all currently installed packages
* Set-up SSH keys for user grader
* Disable root login
* Change SSH port from 22 to 2200
* Configuration Uncomplicated Firewall (UFW)
* Install Apache to serve a Python mod_wsgi application
* Install and configure PostgreSQL
* Install Flask, httplib2 oauth2client sqlalchemy psycopg2 etc.
* Install Git version control software
* Clone the repository that contains Item Catalog Submission
* Update catalog.wsgi file for this installation
* Update the Google OAuth client secrets file
* Configure Apache2

# Third Party Resources
* https://github.com/iliketomatoes/linux_server_configuration
* https://github.com/vectors36/Udacity_FullStack_Linux
