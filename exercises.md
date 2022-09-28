# AltSchool Cloud-Engineering Exercises

## [Exercise]() 1
### Task: 
* Setup Ubuntu 20.04 LTS on your local machine using Vagrant
### Instruction: 
- [ ] Customize your Vagrant file as necessary with private_network set to DHCP.
- [ ] Once the machine is up, run ifconfig and share the output in your submission along with your Vagrant file in a folder for this exercise.

## [Exercise]() 2
### Task: 
* Research online for 10 more linux commands aside the ones already mentioned in this module. Submit using your altschool-cloud-exercises project, explaining what each command is used for with examples of how to use each and example screenshots of using each of them.

### Instruction:
- [ ] Submit your work in a folder for this exercise in your altschool-cloud-exercises project. You will need to learn how to embed images in markdown files.

## [Exercise]() 3
### Task:
* Create 3 groups – admin, support & engineering and add the admin group to sudoers. 
* Create a user in each of the groups. 
* Generate SSH keys for the user in the admin group.
### Instruction:
- [ ] Submit the contents of /etc/passwd, /etc/group, /etc/sudoers

## [Exercise]() 4
### Task: 
* Install PHP 7.4 on your local linux machine using the ppa:ondrej/php package repo.
### Instruction:
- [ ] Learn how to use the add-apt-repository command
- [ ] Submit the content of /etc/apt/sources.list and the output of php -v command

## [Exercise]() 5
### Task: 
* You already have Github account, aso setup a GitLab account if you don’t have one already.
* You already have a altschool-cloud-exercises project, clone the project to your local system.
* Setup your name and email in Git’s global config.
### Instruction:
Submit the output of:
- [ ] git config -l
- [ ] git remote -v
- [ ] git log

## [Exercise]() 6
### Task: 
* Review the CIS benchmark for ubuntu, and try to implement at least 10 of the recommendations that we made within the benchmark.

### Instruction:
  -  N/A

## [Exercise]() 7

### Task:

* Create a bash script to run at every hour, saving system memory (RAM) usage to a specified file and at midnight it sends the content of the file to a specified email address, then starts over for the new day.

### Instruction:

- [ ] Submit the content of your script, cronjob and a sample of the email sent, all in the folder for this exercise.

## [Exercise]() 8

### Task:
* Create an Ansible Playbook to setup a server with Apache
* The server should be set to the Africa/Lagos Timezone
* Host an index.php file with the following content, as the main file on the server:
```php
<?php
date("F d, Y h:i:s A e", time());
?>
```

### Instruction:
- [ ] Submit the Ansible playbook, the output of `systemctl status apache2` after deploying the playbook and a screenshot of the rendered page

## [Exercise]() 9

### Task:

> 193.16.20.35/29

* What is the Network IP, number of hosts, range of IP addresses and broadcast IP from this subnet?

### Instruction: 
- [ ] Submit all your answer as a markdown file in the folder for this exercise.
