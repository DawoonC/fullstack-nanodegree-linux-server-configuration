# Linux Server Configuration
This project focuses on preparing a given linux instance to host my web applications, which includes installing updates, securing it from a number of attack vectors and installing/configuring web and database servers.

This project, the fifth in [Udacity’s Full Stack Web Developer Nanodegree](https://www.udacity.com/course/nd004), used Linux, Apache, PostgreSQL, and Python stack to set up a server.

## HTTP
The web application, [ND Sharables](https://github.com/DawoonC/nd-sharables/), is hosted via HTTP at the server's IP address: [52.11.224.66](http://52.11.224.66/).

## SSH
To make ssh access to the server, you can use following syntax:
```
$ ssh -i [rsa_file] -p 2200 grader@52.11.224.66
```
1. Create a file in your home directory and name it whatever you want (e.g. mykey).
2. Copy the RSA key from submission note, and paste it into the file created in step 1.
3. Make the file only readable (e.g. `$ chmod 400 mykey`)
4. In your terminal, from your home directory, use the above ssh command to access the server.
 - e.g. `$ ssh -i mykey -p 2200 grader@52.11.224.66`
