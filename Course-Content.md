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





# Pre-Requisite to setup

