#Project Details
> This is a project to build webapp using python flask framework and deploy it on EKS cluster. I am using AWS cloud as target infra. This project use Prometheus and cAdvisor to collect metrics and  Grafana for  visualisation. The entire project is intended to be a container based system which is provisioned on EKS. 

Below are the specs used in this project:
* DockerImage: Creating using Dockerfile
* Configuration Management: Ansible
* IAAS : Terraform
* Cloud provider : AWS
* Docker
* Prometheus
* cAdvisor
* Grafana

### Prerequisites
You should have aws account with  the following resource created:
* AWS access/secret keys
* VPC and subnet
* Key pair 

### Usage :

1) Clone git project to workstation
2) Run the bootstrap ```deploy.sh``` script to setup enviroment 

Script usage:

```sh  deploy.sh -e <environment> -a <app name>  -c <count_instance> -t <instance_type> -u <user_name>```

> deploy.sh will assign AWS variable at the time of execution.
Assign value :
+ AWS Access/Secret key : Use to access you AWS resource
+ key-pair :  will use by ansible for remote login

<em>Note : you can change default value of deploy.sh script from terraform var file here terraform/aws/variables.tf <em>
  
  
 ================================= 


#import OPencv
numpy- module which handles metrics
cv2 - module to open cv
#read the image
img = cv2.imread('homer-simpson.png') - this will store image in img
#do the processing
#show image
cv2.imshow('image',img) - image window
#close n exit
cv2.waitKey(0)
cv2.destroyAllWindows()

====== code

00:01:24 root@:/opt/flask# ls
__pycache__  app.py  requirement.txt  static  templates
