# DNS-practice

In this repository, we linked a purchased domain name to an existing IP address. GCP was where we created the virtual machine (VM). 

## A Record:

Name: ramony.tech

Value: 35.188.17.180

TTL: 7200

## Brief Instruction to re-create

The purchased domain name is "ramony.tech" from get.tech.com. Create the VM and have the IP address ready. After you pruchased the domain name, we will nagivate to the control panel and can see our domain name that we brought. Then we scroll down to DNS Management, click on Managae DNS, and click on "Add A Record (it should be the first record shown when you click on Manage DNS). After you click add A Record it will show Name, Value, TTL. You will input the Name (ramony.tech), Value (35.188.17.180) which is the IP address from the GCP VM, TTL (7200). In the VM terminal, you will connect to a github repo and connect to the flask app file. Afterwards, you will be able to access the app from ramony.tech

## Commands in the VM terminal

sudo apt-get update

sudo apt install python3-pip

pip3 install flask

sudo apt install python3-flask

git clone git-repo-link

sudo python3 app.py
