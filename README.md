# AWS-Projects
This is the website where I displayed the following AWS Projects.

# Multitier Web Application
You will find how I initially built the website the "traditional way" by using an instance running all the time with a load balancer pointing at a target group of 1 minimum, 1 desired and 1 maximum instance for high availability. The launch template attached to the target group was automated to install Apache and clone my private repository to the Apache folder.

Open 

# Serverless Web Deployment
This is a walkthrough of the current website architecture. The website is hosted in a private repository that is linked to a CloudFront distribution for security and low latency purposes. With the use of CodePipeline, any updates that are "pushed" to the CodeCommit repository are automatically uploaded to the bucket.

Moreover, you will find a bash script created for backup automation and a video of how to migrate from Git to CodeCommit.


