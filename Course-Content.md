# Course Content



Step-I



1\. Basics of Linux

2\. Server Management in Linux

3\. Vagrant

4\. Basics of networking

5\. Vprofile Project Intro \& Setup on VM's



Step-II



1\. Cloud Computing Intro | AWS

2\. IAM

3\. Ec2 Instances, EBS Volumes

4\. ELB

5\. Autoscaling

6\. Route53

7\. Vprofile Project setup on AWS cloud



Step-III



1. GIT
2. Maven
3. Jenkins
4. CI/CD
5. CICD Pipelines
6. Nexus
7. SonarQube
8. Jenkins Administrations
9. Pipeline As A Code



Step-IV



1. Bash Scripting
2. Vars, Conditions, Loops etc
3. Automating day to day admin task
4. Python programing basics
5. Vars, datatypes, conditions
6. Loops, functions, modules etc
7. Python for automating OS tasks



Step-V



1. Ansible Intro
2. Ad Hoc commands
3. Modules
4. YAML intro
5. Playbooks
6. Vars, conditions , loops, handlers, templates etc
7. Var deep dive and Roles
8. Ansible for AWS



Step-VI



1. AWS part 2
2. VPC in depth
3. Log management and custom metrics
4. CloudWatch
5. AWS Cli \& S3 cli
6. Beanstalk on RDS
7. Vprofile on BeanStalk
8. Code Commit , Code Build \& Code Pipeline



Step-VIIa



1. Docker Intro
2. Understandin and Implementing Containers
3. Volumes, Network , logs etc
4. Building Images for Vprofile project
5. Docker compose to run vprofile multi containers



Step-VIIb



1. Kubernetes Intro
2. Kubernetes setup for production Env
3. Kubernetes objects
4. Pods, Services, Controllers
5. Deployment Replication, Autoscaling
6. Resource Quotas, secret , configmap, namespace



Step-VIII



1. Cloud Automation with Teraform

2\. CloudFormation





**Date :- 5-10-2025**



# Software Development Process (SDLC)



1. Requirement Gathering \& Analysis



Product Features

Users

Usage

User Requirement

Market State



2\. Planning (what do we want?)



Cost, Resources \& Risk



3\. Design Architects



Based on detailed requirement system design documents are created



4\. Development



Software Development Based on Inputs of design documents



5\. Testing Quality Assurance (QA)



Identify the defects to ensure the quality of product is good



6\. Deployment



Operation Works after deploying the product



7\. Maintenance



System health , performance , uptime , regular changes









Entire Process



Requirement Gathering -> Planning -> Designing -> Development -> Testing -> Deploy \& Maintain





# Models in SDLC



1. Waterfall

Requirement -> Designing -> Implementation -> Testing -> Maintain



in this very hard to changes in requirement



2\. Agile

Distribute requirements list in multiple steps once one finish then go on other



in this step Operation team is tired of continue doing this step again and again



regular deploy requests

no clear instruction

already occupied

system uptime

ITIL process driven



3\. Spiral



4\. Big Bang



5\. etc





in this situation dev is AGILE whereas ops is (waterfall) driven





then the role of DevOps come





Collaboration , Communication , Integration





# Automation



Code Build

Code Testing

Software Testing

Infra Changes

Deployment





# DevOps Lifecycle



1. Code (Developers commit the code)
2. Code Build (Deployable Software : Artifact)
3. Code test (Unit \& Integration Test)
4. Code Analysis (best practice)
5. Delivery (Deploy changes to staging)
6. DB/Sec changes (Every other ops changes)
7. Software Testing (QA/Functional , load performance tests)
8. Deploy to prod
9. Go Live (user traffic diverted to new changes)
10. User Approval (user Feedback)
11. Keep Monitoring



# What is Continuous Integration (CI)







developers codes a lot in this situation they need to store the code in a centralized place like version control system (GIT , SVN , etc)



them main aim of CI process is to get earlier defect if found





Continuous integration is a DevOps software development practice where developers regularly merge their code changes into a central repository, after which automated builds and tests are run.



Code -> Build Server -> Artifact Software (Repo)





Artifact file

WAR / JAR (Java)

DLL/EXE/MSI

ZIP/TAR





after code successfully test code shifted to prod





example



develop code for 3 weeks after that code shifted in git after that we see lot of errors .





in this every code commit first build and test



###### Lifecycle



Code -> Fetch -> Build -> Test -> Notify -> Feedback





GitHub (Fetch Code) -> Jenkins (Failure errors)





###### Version Control



1. GIT

2\. SVN

3\. TFS

4\. PERFORCE

5\. etc



###### Build Tools



1. Maven , Ant , Gradle
2. MsBuild, Visual Build
3. IBM urban Code
4. MAKE
5. GRUNT



###### Software Repositories



1. Sonatype Nexus
2. JFFrog Artifactory
3. Archiva
4. CloudSmith Package
5. Grunt



###### CI tools



1. Jenkins
2. CircleCi
3. TeamCity
4. Bamboo Ci
5. Cruise Control



Code -> Code Build \& Test-> Code Analysis -> Artifact Repo -> Deploy Automation -> DB sec/changes -> Software testing -> Schedule prod Deployment



# What is Continuous Delivery



It is automation process of delivery code changes



Continuous delivery is a software development practice where code changes are automatically prepared for a release to production.



If CI part everything good



###### Deployment



1. Server Provisioning
2. Dependencies
3. Conf Changes
4. Network
5. Artifact Deployed
6. many more



###### Tools

1. Ansible, Puppet , Chef
2. Terraform , CFormation
3. Jenkins , Octopus Deploy
4. Helm Chart
5. Code Deploy
6. etc



###### Test Automation



1. Functional
2. load
3. Performance
4. DB
5. Security
6. any other test



# Course Material Link



1. https://github.com/imnowdevops/ddc-material
2. https://github.com/imnowdevops/ddc-material/archive/refs/heads/master.zip





# Chocolaty



This tool is for installing software in laptop through PowerShell command line in windows



we have brew for macos





for installing chocolaty use this command



Set-ExecutionPolicy Bypass -Scope Process -Force; \[System.Net.ServicePointManager]::SecurityProtocol = \[System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))





**Date :- 6-10-2025**



# Pre-Requisite to setup



###### How to purchase a domain



1. Go to godaddy or any domain buying site https://www.godaddy.com/en-in
2. create and login account
3. type your domain id text like navneetdevops.xyz / .com and choose according to your budget
4. click on continue to cart
5. then click on i am ready to pay



###### DockerHub



1. search for dockerhub in browser
2. click on this link https://hub.docker.com/
3. then signup / login
4. choose free if you want free account else go buy it
5. verify your account



###### SonarCloud



1. search for sonarcloud in browser
2. click on this link https://www.sonarsource.com/sem/products/sonarcloud/
3. then click on getting started / sign up
4. choose GitHub and Authorize it



**Date :- 7-10-2025**



###### AWS Setup



1. search for aws free tier in browser
2. click on this url https://aws.amazon.com/free/
3. click on create free account
4. fill details and create account
5. there are two types of user account root (parent) and IAM (sub-account) user
6. setup billing method



AWS setup done



###### SET MFA on root user



this i am user is sub user of account that can use. Root user have all rights whereas IAM user need to give permisions



1. search for iam in search part
2. then first we see Add MFA and then click on it
3. then type Device name that want for IAM name like navneet-admin
4. choose any device from bottom option list
5. i am choosing Authenticator app here after that click on next button
6. first install Microsoft authenticator app then scan for QR code
7. type MFA code 1 and 2 and then click on add MFA
8. after that cred part of that user screen will show



###### Create IAM User



1. i you want to create user then click on users and create user
2. then type user name like itadmin
3. check for Provide user access to the AWS Management Console - (optional) (checkbox)
4. then choose I want to create an IAM user and autogenerated password
5. then click on next
6. then you need to set permission
7. in this you can choose any of this option (Attach policies directly)
8. in policies search for policy you want to give
9. i am choosing AdministratorAccess you can give more
10. then click on next
11. please set tag also it is best practice
12. then click on create user



after that share these details to the user then user login it and reset its password



you can set MFA for this also by same steps.



###### Set Billing Alarms



we can set billing alarms through cloud watch. steps given below



1. click on user name dropdown in top right corner
2. then click on billing and cost management
3. click on billing prefrences
4. we need to enable active three options available in top (PDF invoices delivery by email, AWS Free Tier alerts, CloudWatch billing alerts)
5. then click on aws logo in top left
6. then search for CloudWatch in website
7. then click on alarms and create if no alarm / or want to create more
8. choose select metric
9. choose billing and then total estimated charge
10. check usd then click on select metric
11. under condition type for amount (0.1 ex) and then click on next
12. in notification either you chose SNS (Simple Notification System) or create topic
13. under create top type alarm name like AWS\_Billing\_Amount and choose email where to send (this alarm is only for selected region for separate region need separate alarm)
14. then click on next
15. under alarm detail page name your Alarm (BillingAlert)
16. then click on next
17. then click on create alarm



###### Set Certificate Manager



1. search for acm in website
2. click certificate manager
3. click on request a certificate
4. choose Request a public certificate
5. click on next
6. type this \*.<your\_domain\_name> like (\*.hkhinfo.xyz)
7. for validation it have validation method like DNS validation for this we need to go on godady (an domain provider)
8. type for some tag
9. like domain => hkhinfo.xyz
10. then click on request
11. in detail page under domain CNANE name and CNAME value need to enter in domain website like godady
12. click on manage domain then DNS then add record
13. choose things that above and enter it



###### Set Account Alias



1. search for IAM
2. in its dashboard you see AWS Account widget / card in right
3. in Account Alias choose create
4. type alias value (navneetdev)



# Virtualization



one computer can run multiple os at the same time parally in one device



###### Life before virtualization

---

1. To run App/Services we need servers (Tomcat, Apache, MySQL)
2. Physical computers (servers in datacenter)
3. one service - one server(isolation)

suppose if your DB server is running you dont run other things at a time

4\. servers are always over provisioned

(if we need 8 GB of RAM so we add 12 GB of RAM)

5\. server resources mostly underutilized

if OS dont use that extra space so that is underutilized

6\. Huge capital expenditure \& operating cost

Physical server , stack etc maintenance also need



###### What is virtualization



1. Enter VMWare
2. Allows one computer to run multiple OS
3. partition physical resources in virtual resource
4. virtual machines runs in isolated ENV
5. server virtualization is the most common virtualization



Application	Application	Application

Windows		Linux		Suse Linux

VM		VM		VM

Hypervisor

Hardware



###### Terminologies



Host OS => OS that installed on laptop / desktop

Guest OS => virtual machine

Snapshot => Backup of VM (Set of files)

Hypervisor => VM tool



**Type 1**



1. Bare Metal

2\. Runs as a Base OS (windows 10, macos, Linux , etc)

3\. production



eg VMware esxi, Xen Hypervisor



VM1		VM2

App		App

Guest OS	Guest OS

Type-1 Hypervisor

Hardware (CPU, Memory, Interrupts)



type-1 hypervisor can be cluster together



**Type 2**



1. Run a Software
2. Lear \& Test
3. eg. Oracle virtualbox, VMware server





 		VM

 		App

 		Guest OS

App		Type-2 Hypervisor

Native OS

Hardware (CPU, Memory, Interrupts)



**Date :- 09-10-2025**



# VM Setup



###### Linux VM's



1. CentOS VM
2. Ubuntu VM



###### Methods to create



1. Manual

for starting we need to enable these setting

Enable Virtualization in BIOS



for go into BIOS you need to f2, f12, delete, esc

having by these name :- vtx / Secure virtual machine / Virtualization



we need to disable some settings



a. search for windows PowerShell in windows search
b. turn windows feature on or off in windows search



disable these settings



a. Microsoft HyperV
b. Windows Hypervisor platform
c. Windows Subsystem for Linux
d. Docker Desktop
e. Virtual Machine Platform



IF VM not getting IP address reboot system



a. power off our computer
b. reboot router / wifi
c. power on your compter



###### Create Virtual Machine



search for Oracle VirtualBox in windows search

for check virtual box version click on help > about virtual box



click on new for setup



a. type VM name (centos)

b. folder decide where virtual box stored

c. type choose decide its type (Linux)

d. sub type define sub type of that (RedHat)

e. in hardware part decide space of Hard disk and ram allocation (after decide space and ram) click on next

f. selected details  will show if you all ok then click on finish



for installing os you need to download ISO



###### CentOS

search for centos stream 9 iso download in chrome



click on this link :- https://mirror.stream.centos.org/9-stream/BaseOS/x86\_64/iso/



click on this file CentOS-Stream-9-20251008.0-x86\_64-boot.iso



for add ISO click on setting then storage

Controler.IDE > Empty  > dropdown > Choose a Disk File

then click on Live CD/DVD

then click on ok



after that we need to set for network adapter



click on setting then Network

first you see Adapter one with its value NAT don't do anything with it work on Adapter 2

after choose Adapter 2 enable it

choose attached to as bridge adapter



after that click on ok



then click on settings in sytem > pointing device

choose USB Tablet to pointing in VM's



after these thing close all and start OS by double tap



after select first setting



choose language then done

after that in installation destination choose partition disk that showing

under network \& host name choose enpos8 secondary because of bridge adapter

set root password

then click on begin installation

after installation we need to remove iso otherwise re-installation

type username and full name => centosuser

type password => (pass@123)



192.168.86.9/24



ssh <username>@<ipaddress>



eg.

ssh centosuser@192.168.86.9





###### Ubuntu Server



search for in Ubuntu Server chrome



in url list some Jelly Fish thing available that need to be click

click on this link :- https://releases.ubuntu.com/jammy/



choose Server install image for download



do same procedure for installation this os like CentOS





ssh <username>@<ipaddress>



eg.

ssh centosuser@192.168.86.9



hostname => provide the hostname of OS





2. Automation



through **vagrant** we can do automation of VM's LifeCycle



Vagrant solve these problems

=> when we create VM manually many issues with that :-

a. OS installation => many steps to perform for install VM

b. Time Consuming => Many steps you go through. it take so much time in install



multiple VM \* VM's

c. Manual => Human Error

d. tough to replicate multi VM's on other or same system

need to document entire setup



Vagrant for VM's

a. No os installation

   VM images/Box

free box available on vagrant cloud



###### Vagrant file



=> manage all VM setting in a file

=> VM change through vagrant file

=> provisioning (when the os is completelly booted you want to execute some commands on it) may be setting some DB server



###### Simple Commands



a. vagrant init boxname => vagrant file download

b. vagrant up => running server/start (create)

c. vagrant ssh => login

d. vagrant halt => stop server

e. vagrant destroy => delete VM



###### Vagrant Architecture



Box/Image --------

 		  |

 		Vagrant ------------------	---------------------------  Oracle VirtualBox (Hypervisor) -------------------------------------------	 VM1

 					 |	|												      |

vagrant up  ---------------------------- |	|												      -- VM2

vagrant halt/reload/destroy ------------ Vagrant file (VM Info, Boxname , Networ , Provisioning , Sync dir , memory/cpu, disksize , etc)	      |

vagrant ssh , etc ---------------------- |													      -- VM3



# 

###### Steps



Folder -> Vagrant File -> vagrant up -> vagrant ssh -> vagrant halt/destroy



halt => power off vm

destroy => delete vm

# 

vagrant cloud contains all vagrant box/images



###### CentOS through vagrant



https://portal.cloud.hashicorp.com/vagrant/discover/eurolinux-vagrant/centos-stream-9



vagrant init eurolinux-vagrant/centos-stream-9



cat Vagrantfile



vagrant up



vagrant status => will show status of vm is running or not



vagrant ssh => it will login root user automatically



sudo -i => this will swith user to root user



vagrant reload => this will re download varant file and install it (box namewill not change in this case for that destroy vm need)



vagrant destroy



vagrant box list => this will give all virtual box list



vagrant global-status => this will show you running status of all VM's



###### Ubuntu through vagrant



https://portal.cloud.hashicorp.com/vagrant/discover/ubuntu/jammy64



vagrant init ubuntu/jammy64



# some Linux commands



in this choose means tab button press



a. ip addr show => this show ip address of os



mostly select done when partion part come then also done after that continue



your name => Navneet

server name => ubuntuvm

pick a user name :- devops

password => pass@123

confirm password => pass@123



after that click on done than continue



then ssh configuration part come



choose for Install OpenSSH Server



after that screen do nothing just choose done



ssh devops@192.168.86.10





**for see in GitHub use this**



ssh <username>@<ipaddress>



eg.

ssh centosuser@192.168.86.9



hostname => provide the hostname of OS



pwd => present working directory

mkdir => this is for creating folder in active directory . eg :.= mkdir navneet

ls => ls command is see all the folders and files of active folder

whoami => will show current logged username

history => this will show all executed command history



**Date :- 10-11-2025**



# Linux



###### Topics Cover



1. Intro to Linux
2. Basic CLI commands
3. Understanding files in Linux
4. Filters \& Redirection
5. Users \& Group
6. Sudo
7. Software Management
8. services \& Process
9. Good to know comments
10. Server Management



###### Open Source



open source software is software with source code that anyone can inspect , modify and enhance, redistribute.



History



It is an open source OS



**1984**

=> The GNU Project and the free software foundation

=> Creates open source version of Unix utility

=> Creates the general public licence (GPL)



**1991**

Linux go towards

=> Creates open source Unix like kernel , release under the GPL

=> ports some GNU utilities , solicit assistance online



**Today**

=> Linux kernel TGNU utility = complete open source , Unix like OS



###### Linux Principles



1. Everything is a file (including hardware)
2. Small single purpose programs
3. ability to chain programs together for complex operations
4. avoid trapped user interface (No Graphic Software)
5. Configuration data stored in text files



###### Why Linux



1. Open Source
2. Huge community support / New updates
3. support wide variety of hardware's (mobile , laptop , server, etc)
4. most servers run on Linux
5. automation is easier than windows
6. security



###### Architecture of Linux





please see image :- https://www.tutorialspoint.com/operating\_system/images/linux\_architecture.jpg



or



fig.1.linux-architure.jpg



Popular Desktop Linux OS / distros



1. Ubuntu Linux
2. Linux mint
3. Arch Linux
4. Fedora
5. Debian
6. OpenSUSE



Popular Server Linux OS



1. Red Hat Enterprise Linux => Not Open Source
2. Ubuntu Server
3. CentOs
4. SUSE Enterprise Linux



Most Popular Linux distros current in IT industry



**RPM based** :- RHEL, Centos, Oracle Linux

package extension => exe, msi , apk



RHEL , CentOS, Oracle Linux



installation file for red hat based distribution



**Debian based** :- Ubuntu Server, Kali Linux

package extension => deb



installation file for Debian based distribution



Ubuntu Server , Kali Linux



major difference in both is package based



Some Important Directories(folders)



1. Home directories :- /root , /home/username
2. User Executables : - /bin, /usr/bin, /usr/local/bin
3. System Executables :- /sbin, /usr/sbin, /usr/local/sbin
4. Other Mountpoints:- /media, /mnt
5. configuration :- /etc
6. Temporary file :- /tmp
7. Kernels \& bootloader :- /boot
8. Server Data:- /var, /srv
9. System Information :- /proc, /sys
10. Shared libraries :- /lib, /usr/lib, /usr/local/lib
