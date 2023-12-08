# Directories where file should go

- backend binary, hello-server, goes to /var/www/ directory
- frontend, index.html, goes to /var/www/my-site directory
- nginx configuration file, hello.conf, goes to /etc/nginx/sites-available directory
    - a symbolic link of this hello.conf goes to /etc/nginx/sites-enabled directory
- config for setting up servers, cloud-config.yml, is used in DigitalOcean before setting up both web1 and web2 servers
- curl commands for testing server, curl.md, has my load-balancer IP address. 


## Included material

- *unedited* backend binary, hello-server
- *unedited* frontend, index.html
- *edited* nginx configuration file, hello.conf
- *edited* service file for backend, hello-server.service
- *edited* config for setting up servers, cloud-config.yml
- *edited* example curl commands for testing your server, curl.md


# Linux Assignment 3 part 2 Info

This assignment uses a starter file from https://gitlab.com/cit2420/as3p2-starter-f23
The included backend server runs on port 8080, 127.0.0.1:8080
