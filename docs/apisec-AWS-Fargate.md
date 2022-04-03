# APIsec AWS Fargate


###### AWS Fargate<sup>TM</sup> - Some Text - 


## APIsec AWS Fargate

!!! example "Deployment of APIsec Scanner in AWS Fargate"

	- Login into AWS Account
	- Select Amazon Elastic Container Service (ECS)
	- Select Clusters
	- Create a New Cluster
	- Select "Networking Only" Option
	- Give Unique Cluster Name
	- Skip VPC and CloudWatch option,Click on create 
	- Select View Cluster
	- Task Definitions
	- Create a New Task Definition
	- Select 'FARGATE' Option
	- Followed by Next, Give Unique Name & Select the rest options as provided
	- Add Container
	  Select atleast below mentioned CPU and Memory to run scans on playbooks smoothly.
	- Give Unique Container name and Image name
	- Skip all options & proceed on “Environment variables” section to add scanner parameters from scanner created page of APIsec
	   Optional :- Log configuration 
	 - Add Container
	 - Click on Create
	 - Redirect to home page, then Click on Newly Created Cluster
