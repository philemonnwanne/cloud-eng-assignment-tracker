# AltSchool Cloud-Engineering Exercises

## [Exercise]() 1
### Task: 

* Setup a stateless application on 3 EC2 instances behind an Elastic load balancer running Nginx Web server. 
Your application should display the hostname of the server serving the content at that time. 
Use a programming language of choice, you can use Google to cook up something that works if your programming knowledge isn’t strong.

### Instruction:
- [ ] Point a subdomain to ELB and submit it with the application

  ### [Solution]()


## [Holiday]() Challenge

### You are required to perform the following tasks
* Set up 2 EC2 instances on AWS(use the free tier instances).
* Deploy an Nginx web server on these instances(you are free to use Ansible)
* Set up an ALB(Application Load balancer) to route requests to your EC2 instances
* Make sure that each server displays its own Hostname or IP address. You can use any programming language of your choice to display this.
* Work on building a personal portfolio and CV (Check out resumeworded.com).


### Important points to note:
- [ ] I should not be able to access your web servers through their respective IP addresses. Access must be only via the load balancer
- [ ] You should define a logical network on the cloud for your servers.
- [ ] Your EC2 instances must be launched in a private network.
- [ ] Your Instances should not be assigned public IP addresses.
- [ ] You may or may not set up auto scaling(I advice you do for knowledge sake)
- [ ] You must submit a custom domain name(from a domain provider e.g. Route53) or the ALB’s domain name.

  ### [Solution]()



## [Mini]() Project

### You are required to perform the following tasks
* Using Terraform, create 3 EC2 instances and put them behind an Elastic Load Balancer
* Make sure that after applying your plan, Terraform exports the public IP addresses of the 3 instances to a file called host-inventory
* Get a `.com.ng` or any other domain name for yourself (be creative, this will be a domain you can keep using) and set it up with AWS Route53 within your terraform plan, then add an A record for the subdomain `terraform-test` that points to your ELB IP address.
* Create an Ansible script that uses the host-inventory file Terraform created to: 
  * install Apache
  * set timezone to Africa/Lagos
  * display a simple HTML page that displays content to clearly identify on all 3 EC2 instances.
* Your project is complete when one visits `terraform-test.yoursdmain.com` and it shows the content from your instances, while rotating between the servers as your refresh to display their unique content.
* Submit both the Ansible and Terraform files created

  ### [Solution]()


## [K8S Mini]() Project

### You are required to perform the following tasks
* Build a simple personal website and packge it in a container image based off of Nginx and publish it on the Docker registry.
* Create a Google Kubernetes Engine (GKE) cluster on GCP with at least 2 nodes and crete a deployment with your website image. Make sure it is publicly available.
* Submit the Dockerfile and Kubernetes manifest for this project along with a screenshot of the website visible in your browser. Please clean up to avoid generating unnecessary cost.

  ### [Solution]()
