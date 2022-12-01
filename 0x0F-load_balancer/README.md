# 0x0F. Load balancer

## Resources

- [Introduction to load-balancing and HAproxy](https://www.digitalocean.com/community/tutorials/an-introduction-to-haproxy-and-load-balancing-concepts)
- [HTTP header](https://www.techopedia.com/definition/27178/http-header)
- [Debian/Ubuntu HAProxy packages](https://haproxy.debian.net/)

## Requirements
General
- Allowed editors: ```vi```, ```vim```, ```emacs```
- All your files will be interpreted on Ubuntu 16.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass Shellcheck (version 0.3.7) without any error
- The first line of all your Bash scripts should be exactly ```#!/usr/bin/env bash```
- The second line of all your Bash scripts should be a comment explaining what is the script doing

## Table of contents
Files | Description
----- | -----------
[0-custom_http_response-header](./0-custom_http_response-header) | Bash script configuring a brand new Ubuntu server with Nginx so that its HTTP response contains a custom header
[1-install_load_balancer](./1-install_load_balancer) | Bash script configuring a brand new Ubuntu server and adds HAproxy with version equal or greater than 1.5
[2-puppet_custom_http_response-header.pp](./2-puppet_custom_http_response-header.pp) | Puppet manifest configuring a brand new Ubuntu server with Nginx so that its HTTP response contains a custom header
