Christopher Shaw
Linux Server Configuration

Server is located at IP 54.152.227.57
SSH port is 2200
Project is hosted to either IP address or may be viewed at http://ec2-54-152-227-57.compute-1.amazonaws.com/

Configuration Changes:
- Disallowed all users but "grader" to SSH connect to server
- Changed SSH port from 22 to 2200
- Set UFW firewall to allow connections from only 2200/tcp, 123/udp, and 80/tcp
- Change Time Zone to UTC

Software Installed:
- Git
- Ntp
- Pip
- Flask
- Sqlalchemy
- Postgresql
- Psycopg2
- Python2.7 dev
- Libjpeg dev
- Zlib1g dev 
- Apache2
- Python Setuptools
- Libapache2 mod Wsgi
- Pillow
- OAuth2Client
- Dicttoxml
- VirtualEnv

Resources Consulted:
http://docs.sqlalchemy.org/en/latest/core/engines.html
https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps
https://www.digitalocean.com/community/tutorials/how-to-configure-ssh-key-based-authentication-on-a-linux-server
https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-12-04
https://github.com/robertavram/Linux-Server-Configuration
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
