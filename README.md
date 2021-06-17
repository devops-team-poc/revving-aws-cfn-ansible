## Revving Infra deployment from CloudFomation and configuration from ansible.

## Deployment using Cloudformation stack

* newInfra template deploys the whole infrastructure from AWS VPC (network) to public and private subnets, security grops, ec2 instances and RDS DB.

* elasticCacheDynamic template deploys the redis cluster for caching.


## Ansible Configration for React JS and Django
This playbooks configures React JS apps as frontend and Django app as backend.

### Front end Setup Steps

* Configure Nginx server with Let's encrypt SSL.
* Configure a separate user for code management.
* Install all the dependencies for front end app.
* Clone the directories of front end app.
* Build and run yarn.
* Set up the server to serve the client.

### Back end Setup Steps

* Configure Nginx server with Let's encrypt SSL.
* Configure a separate user for code management.
* Install all the dependencies for Back end app.
* Setup backend app.
* Set up the server to serve the client.

### **Note:**  Don't forgot to edit the email address, domain names and git repo links.
