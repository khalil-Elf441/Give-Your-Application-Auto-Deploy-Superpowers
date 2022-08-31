# Section 1: Selling CI/CD to your Team/Organization

Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.

[presentation](presentation.pdf)

# Section 2: Deploying Working, Trustworthy Software

Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.

## Build Jobs that failed because of compile errors [SCREENSHOT01]
![SCREENSHOT01.png](SCREENSHOT01.png "SCREENSHOT01.png")

## Failed unit tests Backend[SCREENSHOT02]
![SCREENSHOT02-backend.png](SCREENSHOT02-backend.png "SCREENSHOT02-backend.png")
### Failed unit tests fixed
![SCREENSHOT02-backend-ok.png](SCREENSHOT02-backend-ok.png "SCREENSHOT02-backend-ok.png")


## Failure because of vulnerable packages [SCREENSHOT02]
![SCREENSHOT02-frontend.png](SCREENSHOT02-frontend.png "SCREENSHOT02-frontend.png")
### Failure because of vulnerable packages fixed
![SCREENSHOT02-frontend-ok.png](SCREENSHOT02-frontend-ok.png "SCREENSHOT02-frontend-ok.png")


## Failure because of vulnerable packages. [SCREENSHOT03]
![SCREENSHOT03-backend.png](SCREENSHOT03-backend.png "SCREENSHOT03-backend.png")
### Failure because of vulnerable packages fixed
![SCREENSHOT03-backend-ok.png](SCREENSHOT03-backend-ok.png "SCREENSHOT03-backend-ok.png")


<!---
![SCREENSHOT03-frontend.png](SCREENSHOT03-frontend.png "SCREENSHOT03-frontend.png")
![SCREENSHOT03-frontend-ok.png](SCREENSHOT03-frontend-ok.png "SCREENSHOT03-frontend-ok.png")
-->

## An alert from one of your failed builds. [SCREENSHOT04]
### Email
![SCREENSHOT05.png](SCREENSHOT04-email.PNG "SCREENSHOT04-email.PNG")
### Slack
![SCREENSHOT05.png](SCREENSHOT04-slack.PNG "SCREENSHOT04-slack.PNG")


Utilize a configuration management tool to accomplish deployment to cloud-based servers. 

## Console output of appropriate failure for infrastructure creation job (using CloudFormation). [SCREENSHOT05]
![SCREENSHOT05.png](SCREENSHOT05.png "SCREENSHOT05.png")
### Failure for infrastructure creation job fixed
![SCREENSHOT05-fix-bug.png](SCREENSHOT05-fix-bug.png "SCREENSHOT05-fix-bug.png")

## Console output of a smoke test job that is failing appropriately. [SCREENSHOT06]
![SCREENSHOT06.png](SCREENSHOT06.png "SCREENSHOT06.png")

## Console output of a successful rollback after a failed smoke test. [SCREENSHOT07]
![SCREENSHOT07-destroy-ok.png](SCREENSHOT07-destroy-ok.png "SCREENSHOT07-destroy-ok.png")

## Console output of successful promotion of new version to production in CloudFront. [SCREENSHOT08]
![SCREENSHOT08.png](SCREENSHOT08.png "SCREENSHOT08.png")

## Console output of successful cleanup job that removes old S3 bucket and EC2 instance. [SCREENSHOT09]
![SCREENSHOT09.png](SCREENSHOT09.png "SCREENSHOT09.png")

## Evidence that the deploy jobs only happen on the master branch. [SCREENSHOT10]
![SCREENSHOT10.png](SCREENSHOT10.png "SCREENSHOT10.png")

## Evidence of deployed and functioning front-end application in an S3 bucket [URL02].
![URL02_SCREENSHOT.PNG](URL02_SCREENSHOT.PNG "URL02_SCREENSHOT.PNG")

## Evidence of deployed and functioning front-end application in CloudFront. [URL03_SCREENSHOT]
![URL03_SCREENSHOT.PNG](URL03_SCREENSHOT.PNG "URL03_SCREENSHOT.PNG")

## Evidence of healthy back-end application. [URL04_SCREENSHOT]
![URL04_SCREENSHOT.png](URL04_SCREENSHOT.png "URL04_SCREENSHOT.png")

# Section 3: Turn Errors into Sirens

Surface critical server errors for diagnosis using centralized logging.

## Evidence of Prometheus Server. [URL05_SCREENSHOT].
![URL05_SCREENSHOT.png](URL05_SCREENSHOT.png "URL05_SCREENSHOT.png")

## Evidence that Prometheus is monitoring memory, cpu and disk usage of EC2 instances. [SCREENSHOT11]
## CPU
![SCREENSHOT11-node_cpu_seconds_total.png](SCREENSHOT11-node_cpu_seconds_total.png "SCREENSHOT11-node_cpu_seconds_total.png")
## Disk
![SCREENSHOT11-node_disk_write_time_seconds_total.png](SCREENSHOT11-node_disk_write_time_seconds_total.png "SCREENSHOT11-node_disk_write_time_seconds_total.png")
## Memory
![SCREENSHOT11-node_memory_MemFree_bytes.png](SCREENSHOT11-node_memory_MemFree_bytes.png "SCREENSHOT11-node_memory_MemFree_bytes.png")

## Evidence that Prometheus and AlertManager send alerts when certain conditions exist in the EC2 instance. [SCREENSHOT12]
![SCREENSHOT12-trigger-alerts](SCREENSHOT12-trigger-alerts.PNG "SCREENSHOT12-trigger-alerts.PNG")


# URLS

URL 01 - https://github.com/khalil-Elf441/Give-Your-Application-Auto-Deploy-Superpowers

URL 02 - http://udapeople-5927908.s3-website-us-west-2.amazonaws.com/#/employees

URL 03 - d1v86frunby356.cloudfront.net

URL 04 - http://ec2-52-38-152-250.us-west-2.compute.amazonaws.com:3030/api/status

URL 05 - http://ec2-50-112-80-230.us-west-2.compute.amazonaws.com:9090/targets


