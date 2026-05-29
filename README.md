# finalassesment-ict171
my sail results project
52.229.228.34 - sail-results.org

## Before building the website
  Microsoft Azure
 -Create a resource group (location: Australia East)
 -Create a vertial machine ; operating system, Linux(ubuntu 24.04)
                           Location, East Asia


## Connecting the Azure virtual machine to wordpress
https://shieldstech.com.au/2093-2/
to link your azure vertial machine to wordpress to creat the website
 1. create new apache configoration with
 sudo nano /etc/apache2/sites-available/wordpress.conf  
 2. then go into the link http://<52.229.228.34>/wp-admin.
 
 ## Linking the DNS sail-results.org
 1. after perchacing the personal plan in wordpress it allows you to link your domain name to the website you are making
 2. in your dashboard go to upgrades then Domains
 3. select add new domain --> use a domain I own
 4. type in the domain name then select connect your domain name
 5. click start setup
 6. find your domain provider 
 7. then select advanced set up
 8. from there follow the instruction on what to insert into your domain provider 


  
