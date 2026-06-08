# finalassesment-ict171
my sail results project
52.229.228.34 - sail-resultsorg.wordpress.com
1. Elisabeth E B Smith - 35578124
2. video explainer link - https://youtu.be/bfJUKiQm8Es 

## Before building the website
  Microsoft Azure
 -Create a resource group (location: Australia East)
 -Create a vertial machine ; operating system, Linux(ubuntu 24.04)
                           Location, East Asia
1. when domain name is perchaced and the vm is set up link the DNS by inserting the public IP address into the DNS's records


## Connecting the Azure virtual machine to wordpress
https://shieldstech.com.au/2093-2/
to link your azure vertial machine to wordpress to creat the website
 1. create new apache configoration with
 sudo nano /etc/apache2/sites-available/wordpress.conf  
 2. then go into the link http://<52.229.228.34>/wp-admin.
 3. test the connection works
 
 ## Linking the DNS sail-results.org
 DNS was perchased in cloudflare. $10.47
 1. after perchacing the personal plan in wordpress it allows you to link your domain name to the website you are making
 2. in your dashboard go to upgrades then Domains
 3. select add new domain --> use a domain I own
 4. type in the domain name then select connect your domain name
 5. click start setup
 6. find your domain provider 
 7. then select advanced set up
 8. from there follow the instruction on what to insert into your domain provider 

## Securing the site
Using https://letsencrypt.org/getting-started/
1. first insureyou can ssh into your machine, 
ssh -i pemkey.pem azureuser@sail-results.org (or 52.229.228.34)
2. and that you can see your webpage in a browser
3. ensure that yoyr vm has ports 22, 80 and 443
4. when asked what your using select "Nginx" and "Linux (snap)"
5. then follow the prompts in your teminal

## Make the website
1. add pages for extra content
2. insert text and images into wordpress and continue to check on your terminal
  
