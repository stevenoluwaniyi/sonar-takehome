Things to Note:

AWS profile with administrative permissinos must be used to create all resources


Input Parameters have default values
ASG ARN requires an input in ECS-Cluster file after ASG CF has been run
VPC, Private-Subnet and Public-Subnet need to be run first respectively


Create the stack 

aws cloudformation create-stack --stack-name <stack_name> --template-body file://<file_name>

Update Stack

aws cloudformation update-stack --stack-name <stack_name> --template-body file://<file_name>