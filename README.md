# Course details
1h 53m  Beginner  Released: 8/22/2018

Set up high-performance architecture with NGINX, the industry-standard, open-source web server. NGINX offers speed unmatched by competitors like Apache, on top of bonus features such as load balancing and HTTP caching. Its rising popularity makes NGINX an indispensable skills for web developers, system administrators, and web technologists of all kinds. This beginner-level LinkedIn Learning training course shows you how to install and configure NGINX on a Linux machine, and set up the rest of the pieces you need for the complete LEMP web development stack. Instructor Michael Jenkins also explores the security features of NGINX, such as password authentication, HTTPS, and SSL certificates, and its capabilities as a reverse proxy and load balancer.

## Learning objectives
Installing NGINX on Linux
Configuring a virtual host
Installing PHP and MariaDB for the LEMP stack
Securing sites with NGINX
Creating SSL certificates
Reverse proxies
Load balancing
Skills covered in this course
Nginx
Viewers of this course


## Instructor
Michael Jenkins

# Exercise Files
The exercise files are located in folders named to match the chapter and lesson they accompany.

Inside each folder is a file named Vagrantfile.  Each Vagrantfile contains a definition for a virtual machine running Ubuntu 18.04 LTS.

To boot the VM for a lesson, open a terminal (CMD or Powershell on Windows; Terminal on Mac) and navigate to the directory containing the Vagrantfile you want to use.

Then run the following command to boot up the VM:

        vagrant up

Run the following command to connect to the VM:

        vagrant ssh

You'll be logged into the VM and can then run commands directly on the VM.  

Exit the VM by typing exit or CTRL+D.

To stop the VM, run the following command from your terminal:

        vagrant halt

And to remove the VM, run:

        vagrant destroy

# Solutions
For each section, the "Solution" directory has a completed set up for that lesson.

To use the solution, first stop the VM running in the lesson directory with "vagrant halt".  Then cd into the Solution directory and run "vagrant up".  Investigate the solution by browsing to the demo site or logging in and taking a look at the configuration.
