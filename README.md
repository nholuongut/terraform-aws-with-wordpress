# Terraform AWS with Wordpress

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

This is to set up wordpress using AWS infrastructure. We are using terraform to provision infrastructure. Code uses and creates following aws services.

1. VPC and it's components
2. Subnets, Route Tables, Internet Gateway, Nat Gateway.
3. EC2 instance
4. EIP for NAT Gateway
5. RDS mysql instance.
6. Security Groups to access both EC2 and MYSQL

Note:  
-----
You may get charged by aws for using services


### Pre-requisite:

   1. You need to have Ssh keys generated and should be put into `~/.ssh/` , if your machine is windows then feel free to use diff path and update the same in the `ssh_key` variable in the `vars.tf`

   2. create an IAM user and create security credentials(AccessKey, SecretKey) and update in the `~/.aws/credentials` file correct as your user.
   
   __Note__ : if you have default profile, just erase the `profile` attribute in `provider.tf`


Usage:
=======

provisioning:
-------------

1. git clone https://github.com/nholuongut/terraform-aws-with-wordpress.git
2. cd terraform-aws-with-wordpress
2. terraform init
3. terraform plan
4. terraform apply -auto-approve

Destroying the Infra:
---------------------
1. cd terraform-aws-with-wordpress (Be in the repo directory)
2. terraform destroy -auto-approve

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
