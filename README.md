# DNS-practice
- Name of Domain: brittanykus.tech
- 'A' record settings
  - @ in 'name' field
  - External IP address in 'Destination IPV4 Address' field
  - 7200 in 'Time-to-live (TTL)' field
- Cloud Vendor: GCP
## Create a .tech DNS

## Create and styilize a web application with many pages.

### First Steps
- load in packages | https://github.com/Brittanykusi/flask-html/blob/2ad078988ccccb1beba05253195645fd234f711d/Script/flaskapp-html.py#L1
- Add routes to pages | https://github.com/Brittanykusi/flask-html/blob/2ad078988ccccb1beba05253195645fd234f711d/Script/flaskapp-html.py#L3-L7
- provide connection to port from local machine | https://github.com/Brittanykusi/flask-html/blob/2ad078988ccccb1beba05253195645fd234f711d/Script/flaskapp-html.py#L31-L32

### Set-up templates
- example | https://github.com/Brittanykusi/flask-html/blob/9fa5d6052ee0126f0a0f2e23f3175510e3a32407/Script/templates/p1_homepage.html#L1-L10

### Set-up Static
- static can be seen as preset features of the webapplication in regards to stylizing
- example | https://github.com/Brittanykusi/flask-html/blob/9fa5d6052ee0126f0a0f2e23f3175510e3a32407/Script/static/styles.css#L1-L23

### connect templates to routes 
- example | https://github.com/Brittanykusi/flask-html/blob/9fa5d6052ee0126f0a0f2e23f3175510e3a32407/Script/static/styles.css#L1-L23

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
- add a link | https://github.com/Brittanykusi/flask-html/blob/f897e85d08535f0ce0ea98071a3e42221abd178c/Script/templates/p1_homepage.html#L5
- attach a photo | https://github.com/Brittanykusi/flask-html/blob/f897e85d08535f0ce0ea98071a3e42221abd178c/Script/templates/p3_patient_landing_page.html#L20
- create a buttion | https://github.com/Brittanykusi/flask-html/blob/f897e85d08535f0ce0ea98071a3e42221abd178c/Script/templates/p2_login1.html#L9
- pull in the css static package of choice | https://github.com/Brittanykusi/flask-html/blob/f897e85d08535f0ce0ea98071a3e42221abd178c/Script/templates/p2_login1.html#L4-L5
