
A basic Docker Compose file to launch a container for WordPress and a second for MySQL.

- Launch this with 'docker-compose up'
- Then connect to http://localhost:8080/ to go through the WordPress installation process.

**NOTE: YOU SHOULD CHANGE THE PASSWORDS** in the file (but make sure WORDPRESS_DB_PASSWORD and MYSQL_PASSWORD
are the same.

A "wp-content" directory will be created in your current directory which will hold themes, 
plugins and other content you add to your WordPress installation.

Credit to @wglambert on Github: https://github.com/docker-library/wordpress/issues/346#issuecomment-435975469

