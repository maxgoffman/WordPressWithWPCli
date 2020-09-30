# WordPress With WP CLI Docker Project
A simple docker compose example project that implements a WordPress Image with WP Cli installed.

## Installation
Prerequisites: Docker and Docker-compose up<br />
If you want to use it to migrate a site, you can do so by dumping your site database into ./mysql-dump/sitedumped.sql and uncommenting line 4 of ./docker/install (and line 6 if you need to set a different url).<br />
If you want to install a number of plugins you can do so by adding them in ./docker/install there is an example of such command in line 10.<br />
Also, make sure to configure wp-config.php and the environment variables (using .env or docker-compose.yml) appropriately.<br />
Steps:<br />
1- In your terminal type docker-compose up -d<br />
2- Next, type docker/install

## Author
[Max Goffman] (https://github.com/maxgoffman)