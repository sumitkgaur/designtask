# Designtask
Infrastructure-as-Code  

Created AWS cloudformation template to provision the infrastructure for a traditional 3-tier architecture in AWS .   
Using PHP, Apache and S3 

AWS services used :   

AWS::EC2  
AWS::ElasticLoadBalancing::LoadBalancer  
AWS::AutoScaling::AutoScalingGroup  
AWS::EC2::SecurityGroup  
AWS::S3::Bucket  
AWS::CloudFormation::WaitCondition  

Infrastructure Diagram :  
Uploaded in the repository  

Steps:  
1. Create a key pair in AWS environment
2. Go to AWS cloud formation and create new stack using template given in repository.   
Just select the Key created in previous step.  
3. Once CREATE_COMPLETE flag appear then go to OUPUT tab and click on applicaiton url to see PHP page  



