# DNS Practice
## HHA 504

Domain Name: crisrib.tech

A Record:
Name: @
Value: 35.238.251.156
TTL: 7200

Cloud Server Used: GCP

Instructions:

Step 1: Create a Domain Name
    
    1.a. Go to (https://get.tech/)
    
    1.b. Search your preferred domain name to purchase it if its available
    
    1.c. Complete purchase (link up student github account for free)


Step 2: Create a Virtual Machine
    
    2.a. Go to GCP
    
    2.b. Create a VM with these specifics:
        
        machine type: e2-micro
        
        Ubuntu 1804
        
        Allow HTTP traffic
        
        Allow HTTPS traffic


Step 3: Run Flask on Virtual Machine
    
    3.a. Open the SSH for the VM
    
    3.b. Enter 'sudo apt-get update'
    
    3.c. Enter 'sudo apt install python3-pip'
    
    3.d. Enter 'pip3 install Flask'
    
    3.e. Git clone URL
    
    3.f. Enter 'nano app.py'
    
    3.g. Enter 'cd'
    
    3.h. Enter 'sudo python3 app.py'


Step 4: Run Flask on Domain
    
    4.a. Go to (https://get.tech/)
    
    4.b. Login
    
    4.c. Click on 'Manage Orders' then 'List/Search Orders'
    
    4.d. Click on the domain name
    
    4.e. Click on 'DNS Management'
    
    4.f. Click on 'Manage DNS'
    
    4.g. Click on 'A Records'
    
    4.h. Add A Record with these specifics:
        
        Host Name: '@'
        
        IP Address: 'insert IP'
        
        TTL: '7200'
    
    4.i. Click 'Add Record'