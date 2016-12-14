# Practical work TP e10

## Preparation

In virtualbox create 3 virtual machines from the ova file provided by the instructor : 

 - server
 - user1
 - admin

Set up a secondary interface on internal network "admin_network" for machines : "server", "admin"

Set up a secondary interface on internal network "public_network" for machines : "server", "user1"

## Setting up network

Q1 : Set up a static address for admin VM on admin_network : 157.159.46.102/24

Q2 : Set up a static address for server VM on admin_network : 157.159.46.103/24

Q3 : Set up a static address for user1 VM on public_network : 157.159.10.2/24

Q4 : Set up two static address (using one network card) on public_metwork for VM server : 157.159.10.3/24 and 157.159.10.4/24

## Setting up firwall

Q1 : Switch your server to a more secure mode : DROP all incoming traffic

Q2 : Write a rulle to allow SSH connection on the admin interface in the admin network

Q3 : Set up a rule to allow port 80 (webserver) on both network

Q4 : limit ICMP rate at 10/s

Q5 : Do not check already setted up connections

Q6 : Allow loopback interface

Q7 : Drop a bad combinaison of SYN flags

Q8 : Black list an IP

Q9 : White list an IP

Q10 : Add more blacklists. Create a chain for it.
