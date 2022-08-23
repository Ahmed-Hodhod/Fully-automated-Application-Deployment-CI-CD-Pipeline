# Fully Automated Application Deployment CI/CD Pipeline using CircleCi

This project is meant to implement a complete CICD pipeline to start once there is a push to the master branch. The pipeline is nearly 12 jobs running on the code to make sure it is bug-free and reliable before deployment. 

### The final output in bullet points: 
- Deploy Infrastructure using AWS CLI commands and CloudFromation Templates.
- Configure the provisioned backend EC2 instance using Ansible Playbooks and Roles.
- Migrate the Database to an RDS-Postgres database on AWS and integrate it into the provisioned EC2.
- Deploy application Frontend UI and host it on AWS S3 as a static website.
- Deploy application Backend Code on EC2 and open PM2 server on port 3030 using Ansible.
- Smoke Test the whole deployment process to ensure the  application is working as intended.
- Promote the application on CloudFront CDN utilizing (Blue/Green) Deployment Strategy.



## The pipeline scheme
![The pipeline flow](udapeople-pipeline.png)

## A push reposity passing all pipeline jobs 
![successful push to repo](https://github.com/Ahmed-Hodhod/Fully-automated-Application-Deployment-CI-CD-Pipeline/blob/master/project_screenshots/Screenshot%20(2129).png)


## A successful rollback on failure 
![Running API](https://github.com/Ahmed-Hodhod/Fully-automated-Application-Deployment-CI-CD-Pipeline/blob/master/project_screenshots/Screenshot7_SuccessfulRollback.png)


## Setting circleci to send us emails 
![CircleCI Notification](https://github.com/Ahmed-Hodhod/Fully-automated-Application-Deployment-CI-CD-Pipeline/blob/master/project_screenshots/ScreenShot4_Email_Notification.png)


## Cloudfront distribution 
![Cloudfront Distribution](https://github.com/Ahmed-Hodhod/Fully-automated-Application-Deployment-CI-CD-Pipeline/blob/master/project_screenshots/URL3_Screenshot.png)


## Testing the website after deployment
![Functioning website](https://github.com/Ahmed-Hodhod/Fully-automated-Application-Deployment-CI-CD-Pipeline/blob/master/project_screenshots/fix_cloudfrontDomanName.png)


## The API is running successfully 
![Running API](https://github.com/Ahmed-Hodhod/Fully-automated-Application-Deployment-CI-CD-Pipeline/blob/master/project_screenshots/URL4_Screenshot.png)


## Listing Employees through a raw API request
![Running API](https://github.com/Ahmed-Hodhod/Fully-automated-Application-Deployment-CI-CD-Pipeline/blob/master/project_screenshots/fix_api-employees.png)


## Configuring Prometheus for monitoring and troubleshooting
![Prometheus](https://github.com/Ahmed-Hodhod/Fully-automated-Application-Deployment-CI-CD-Pipeline/blob/master/project_screenshots/URL5_Screenshot.png)


## An alert from Prometheus [EC2 went down]
![Prometheus Alert](https://github.com/Ahmed-Hodhod/Fully-automated-Application-Deployment-CI-CD-Pipeline/blob/master/project_screenshots/Screenshot12_EmailNotifi.png)


### Built With
- [Circle CI](https://circleci.com/) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation) Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool
