# How build infrastructure:

* To build networking part of the project, please run this command inside the main project folder:
<br><b>./create.sh udagram ./networking/networking.yml ./networking/networking-params.json</b>

* To build servers part of the project, please run this command inside the main project folder: 
<br><b>./create.sh udagram-servers ./servers/servers.yml ./servers/servers-params.json</b>

* To build jumpbox testing EC2 instance of the project, please run this command inside the main project folder: 
<br><b>./create.sh udagram-jumpbox ./jumpbox/jumpbox.yml ./jumpbox/jumpbox-params.json</b> 

Also, to test project properly you will have to add your own .pem file to access EC2 instance using ssh and to change used S3 bucket name.

![alt text](./My%20Udacity%20Diagram.jpeg)