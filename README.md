# DNS-practice
- Name of Domain: brittanykus.tech
- 'A' record settings
  - @ in 'name' field
  - External IP address in 'Destination IPV4 Address' field
  - 7200 in 'Time-to-live (TTL)' field
- Cloud Vendor: GCP

## Create a .tech DNS
https://get.tech/github-student-developer-pack

<<<<<<< Updated upstream
=======
A copy of the 'A' record settings that you needed to write (name, value, TTL) 

>>>>>>> Stashed changes
## Create and styilize a web application with many pages.

### First Steps
- load in packages | https://github.com/Brittanykusi/DNS-practice/blob/5ac0b9156f7320f3f7a21257223581d0c932e483/Script/flaskapp-html.py#L1
- Add routes to pages | https://github.com/Brittanykusi/DNS-practice/blob/5ac0b9156f7320f3f7a21257223581d0c932e483/Script/flaskapp-html.py#L3-L7
- provide connection to port from local machine | https://github.com/Brittanykusi/DNS-practice/blob/5ac0b9156f7320f3f7a21257223581d0c932e483/Script/flaskapp-html.py#L31-L32

### Set-up templates
- example | https://github.com/Brittanykusi/DNS-practice/blob/5ac0b9156f7320f3f7a21257223581d0c932e483/Script/templates/p1_homepage.html#L1-L10

### Set-up Static
- static can be seen as preset features of the webapplication in regards to stylizing
- example | https://github.com/Brittanykusi/DNS-practice/blob/5ac0b9156f7320f3f7a21257223581d0c932e483/Script/static/styles.css#L1-L23

### connect templates to routes 
- example | https://github.com/Brittanykusi/DNS-practice/blob/5ac0b9156f7320f3f7a21257223581d0c932e483/Script/static/styles.css#L1-L23

## Connect DNS (.tech) to virtual machine/Deloy application
- start a virtual machine
  - to make sure your nm enviroment is condusive for your flask app deployment run these commands
    - `sudo apt-get update`
    - `sudo apt install python3-pip`
    - `pip3 install flask`
- connect DNS to virtual machine
  - create a student .tech domain (link here)
    - in the top right corner, underneath your name, navigate you 'My Account'
    - under manage orders click list/search orders
    - click on your domain name
  - in put values as specified above under 'A' record 
- clone repository to cloud terminal
- find folder the application is housed within your cloud terminal 
- change directory (cd) to the folder
- still within your terminal run (python3 'appname'.py) 


#### How to's
- add a link | https://github.com/Brittanykusi/DNS-practice/blob/5ac0b9156f7320f3f7a21257223581d0c932e483/Script/templates/p1_homepage.html#L5
- attach a photo | https://github.com/Brittanykusi/DNS-practice/blob/5ac0b9156f7320f3f7a21257223581d0c932e483/Script/templates/p3_patient_landing_page.html#L20
- create a buttion | https://github.com/Brittanykusi/DNS-practice/blob/5ac0b9156f7320f3f7a21257223581d0c932e483/Script/templates/p2_login1.html#L9
- pull in the css static package of choice | https://github.com/Brittanykusi/DNS-practice/blob/5ac0b9156f7320f3f7a21257223581d0c932e483/Script/templates/p2_login1.html#L4-L5
