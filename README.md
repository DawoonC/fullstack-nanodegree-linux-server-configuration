# Linux Server Configuration
This project focuses on preparing a given linux instance to host my web applications, which includes installing updates, securing it from a number of attack vectors and installing/configuring web and database servers.

This project, the fifth in [Udacity’s Full Stack Web Developer Nanodegree](https://www.udacity.com/course/nd004), used Linux, Apache, PostgreSQL, and Python stack to set up a server.

## HTTP
The web application, [ND Sharables](https://github.com/DawoonC/nd-sharables/), is hosted via HTTP at the server's IP address: [52.11.224.66](http://52.11.224.66/).

## SSH
To make ssh access to the server, you can use following syntax:
```
ssh -i [rsa_file] -p 2200 grader@52.11.224.66
```
- Ensure the rsa file is included.
