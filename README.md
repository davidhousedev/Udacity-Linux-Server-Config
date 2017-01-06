# Udacity-Linux-Server-Config

* IP Address: 35.166.134.229
* Current ssh port: 2200

# Installed Software:
* Git
* PostgreSQL
* Psycopg2
* w3m and w3m-img
* Apache2
  * libapache2-mod-wsgi
* Python 2.7
* pip (and modules)
  * Cheetah==2.4.4
  * Flask==0.10.1
  * Flask-HTTPAuth==3.2.1
  * Jinja2==2.7.2
  * MarkupSafe==0.18
  * PyYAML==3.10
  * SQLAlchemy==0.8.4
  * Werkzeug==0.9.4
  * bleach==1.4.3
  * html5lib==0.999
  * httplib2==0.9.2
  * oauth==1.0.1
  * oauth2client==4.0.0
  * requests==2.2.1
  * urllib3==1.7.1
  * virtualenv==15.1.0
  * wheel==0.24.0

# Configurations Made:
* Updated all software
* Added users 'david' and 'grader'
  * Granted sudo privileges to both users, requring UNIX password entry
  * Created ssh key on local machine and stored public key in david's ~/.ssh/authorized users
  * Set secure UNIX passwords
* Configure firewall
  * Allow SSH on port 2200
  * Allow HTTP on port 80
  * Allow NPT on port 123
  * Disallow all other incoming connections
  * Allow all outgoing connections
* Install and configure Apache2
  * Serve Python Flask web application as a wsgi app from root path
* Disabled remote root access
