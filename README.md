# Devopsfetch Documentation

## Overview
Devops fetch is a tool that fetches system information based off specific commands. It provides information like active ports, user logins, Nginx configurations, Docker images and container statuses. 

## Setup and Installation
Clone the repository and mark the scripts as executable

 1.

 ```console
   git clone https://github.com/The-Chimsom/devops-fetch.git
   cd devops-fetch
 ```
 2.

 ```console
    chmod +x devopsfetch.sh
    chmod +x install.sh
 ```
 3. Run 
 ```console
 sudo ./install.sh
 ```


## Features
 run **./devopsfetch.sh -options** 
 where options can be any of the following
- **-p or --port**  displays all active ports 
- **-d or --docker** displays image and container list or **-d or --docker <container_name>** for container information
- **-n or --nginx** displays all Nginx domains and their ports **--nginx <domain_name>** to give specific configuration information
- **-u 0r --users** to display users and their last logged in time 
- **-u -<username>** to provide specific user info
- **-t or --time <date_and_time>** to show all user logs within a specific time frame
- **-h or --help** to see usage guide and options


