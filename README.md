Terrafrom installation

https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

If you use Windows operating system I recommend upload binary file https://developer.hashicorp.com/terraform/downloads?product_intent=terraform and move .exe file to "C:\Windows\System32" folder
![image](https://user-images.githubusercontent.com/63021874/218686342-e97376c0-bcff-48d8-b7a5-58582966502c.png)

If you have AWS account just install and configure AWS CLI https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

After all installations go under project folder "your_path/simple_aws_infrastructure" and perform next commands

'terraform init' - Prepare your working directory for other commands  
'terraform plan' - Shows changes that will be applyed in Cloud.

If everything is okay then use the following command:
'terraform apply' and enter yes.

Next infrastructure will be built in Cloud:
![Blank diagram](https://user-images.githubusercontent.com/63021874/218694194-b09be79e-c698-437b-9f72-43983bffba8c.png)

