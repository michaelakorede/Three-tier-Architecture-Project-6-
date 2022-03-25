# WEB SOLUTION WITH WORDPRESS 

### In this project, I was asked to prepare storage infrastructure on two Linux servers and implement a basic web solution using WordPress.


    ## "WordPress is a free and open-source content management system written in PHP and paired with MySQL or MariaDB as its backend Relational Database Management System (RDBMS)".

### A. Three-teir Architcture

1. Presentation layer 
2. Business Layer
3. Data Access or management Layer 

    "Three-tier Architecture while also ensuring that the disks used to store files on the Linux servers are adequately partitioned and managed through programs such as gdisk and LVM respectively".
   

B. Your 3-Tier Setup

A Laptop or PC to serve as a client

An EC2 Linux Server as a web server

(This is where you will install WordPress)

An EC2 Linux server as a database (DB) server   

## Step 1: Prepare a Web Server and create 3 volumes in the same AZ as your Web Server EC2, each of 10GiB and attach all three volumes one by one to your web server EC2 instance.






