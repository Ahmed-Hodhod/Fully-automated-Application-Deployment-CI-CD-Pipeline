# Fully Automated Application Deployment CI/CD Pipeline using CircleCi

Through this project, you will be able to Build, Test, and scan the application code as Continues Integration part of the project. Along the way, you will use Continous Deployment Through these steps:
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


## Testing the website after deployment
![Functioning website](https://github.com/Ahmed-Hodhod/Fully-automated-Application-Deployment-CI-CD-Pipeline/blob/master/project_screenshots/fix_cloudfrontDomanName.png)









