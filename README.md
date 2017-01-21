# Linux-Server-Configuration
Linux Configuration project for Udacity's Full Stack Developer Nano Degree

Server Information:

    IP Address: 35.162.99.209

    SSH Port: 2200

Installed Software
  1. Apache2
  2. Git
  3. PostgreSQL
  4. Psycopg2
  5. w3m and w3m-img
  6. Glances
  7. libapache2-mod-wsgi
  8. Python 2.7
  10. pip (and modules)
  11. Cheetah==2.4.4
  12. Flask==0.10.1
  13. Flask-HTTPAuth==3.2.1
  14. Jinja2==2.7.2
  15. SQLAlchemy==0.8.4
  16. Werkzeug==0.9.4
  17. bleach==1.4.3
  18. html5lib==0.999
  19. httplib2==0.9.2
  20. oauth==1.0.1
  21. oauth2client==4.0.0
  22. requests==2.2.1
  23. urllib3==1.7.1
  24. virtualenv==15.1.0
  25. wheel==0.24.0

Configurations:
    1. Added User Grader and Catalog
        Created ssh key on local machine and stored public key in local ~/.ssh/linxProject
        Set secure UNIX passwords
    
    2.Configure firewall
        Allow SSH on port 2200
        Allow HTTP on port 80
        Allow NPT on port 123
        Disallow all other incoming connections
        Allow all outgoing connections
        
    3.Install and configure Apache2
        Serve Python Flask web application as a wsgi app from root path
    4.Disabled remote root access
    
 Reasources Used:
    onfiguring Linux Web Servers - Udacity.com
    Get rid of sudo error message - askubuntu
    Create new ssh user - askubuntu
    More info on UFW - Ubuntu docs
    Change timezone - Ubuntu docs
    Flask App on Ubuntu VPS - DigitalOcean
    python packages not installing in virtualenv using pip - stackoverflow
    Move files from one directtory to another - stack exchange
    Make .git directory web inaccessible
    Fix google + Oauth issue - Udacity Forum
    Using glances - Glances docs
    Use fail2ban to monitor login - digital ocean
    Python 2 in virtual enviroment
    unattended upgardes - ubuntu docs
    Using postgres in flask
