
A basic Docker Compose file to launch a container for WordPress and a second for MySQL.

- Launch this with 'docker-compose up'
- Then connect to http://localhost:8080/ to go through the WordPress installation process.

## NOTES:

- **YOU SHOULD CHANGE THE PASSWORDS** in the file (but make sure WORDPRESS_DB_PASSWORD and MYSQL_PASSWORD
are the same).
- You _may_ need to change the port number 8080 if you have some other service running on that port.
- A "wp-content" directory will be created in your current directory which will hold themes, 
plugins and other content you add to your WordPress installation.

## Acknowledgement

Credit to @wglambert on Github: https://github.com/docker-library/wordpress/issues/346#issuecomment-435975469

I originally [posted a request](https://github.com/docker-library/wordpress/issues/346) for a step-by-step
tutorial about how to use the 'wordpress' Docker image. wglambert was kind enough to come back with a simple
and easy-to-use Docker Compose YAML file.

