# AltSchool Cloud-Engineering Exercises

## [Exercise]() 1
### Task: 

* Setup a stateless application on 3 EC2 instances behind an Elastic load balancer running Nginx Web server. 
Your application should display the hostname of the server serving the content at that time. 
Use a programming language of choice, you can use Google to cook up something that works if your programming knowledge isn’t strong.

### Instruction:
- [ ] Point a subdomain to ELB and submit it with the application


## [Holiday Challenge!!!]()

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
