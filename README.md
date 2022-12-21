[![](https://www.datocms-assets.com/2885/1620155444-blog-library-product-terraform-aws.jpg)](https://www.datocms-assets.com/2885/1620155444-blog-library-product-terraform-aws.jpg)
# AWS Terraform Final Task
**create Terraform code for building the following environment it includes:**
- 2 Load Balancers - Internet Facing and Internal - Create and use a Terraform module
- 4 Web Servers - Create and use a Terraform module
- 4 Application Servers - Create and use a Terraform module
- 1 RDS with two nodes (MySQL)
- 1 S3 Bucket
Assume VPC and subnets already exist "use the default!".


**To run the project locally you have to change the varibales value in the CreateAll.tf file, so it can fit your working Space.**


**Init terraform enivroment:**
```
terraform init

```


**To create an execution plan for your infrastructure run:**
```
terraform plan

```



**To apply the changes outlined in an execution plan to your infrastructure run:**
```
terraform apply -auto-approve

```

**To destroy the resources created by Terraform run:**
```
terraform destroy

```

**The Architict of the system**
![archtict](https://user-images.githubusercontent.com/57920502/208950309-272a46f0-ab40-46e1-bd90-acd25d8e1c91.PNG)

