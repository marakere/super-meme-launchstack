# Deploy OFS SmartContract Accelarator in AWS with one click

About OFS . 
What is OFS SmartContract Accelarator?  
How can I deploy it on AWS?   
How it looks when I deploy it on AWS?  
FAQ's . 





![aws deployment](https://s3.amazonaws.com/ecs-cfn-templates-101/OFSBlockchain.svg)  







<a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=BCBOneClickDeployment&amp;templateURL=https://s3.amazonaws.com/ecs-cfn-templates-101/oneclickdeployment.json" target="_blank"><span class="inlinemediaobject"><img alt="Launch Stack" src="https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/images/cloudformation-launch-stack-button.png"></a>
## Source . 

# FAQ's . 
- Do I need to have AWS account?  
Yes, you need to have AWS account to run the smartcontract accelerator.  
  
- How much it will cost me on AWS to run this application?  
It depends on the EC2 instance size and how long you are running the application. Template provides an opporunity for the users to select the EC2 instance size, application can run in T2.Nana or Micro. We will leave it up to the users to make the choice on the EC2 Instance type.  
  
- Can I delete the application?  
Yes, application can be deleted either by deleting the stack in the cloudformation stack or by terminating the EC2 instance. Preferred approach is to delete from the cloudformation, as it will delete even the security group.  
EC2 Dashboard - https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#Home:  
Cloudformation Dashboard - https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks?filter=active . 


## Licence . 

See [LICENSE](LICENSE) (LifeStartsAt101) . 

