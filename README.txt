CSE-546 Project-2

Group Member Names:
1) Harsh Sanjaykumar Nagoriya (1222471185)
2) Dhruval Vinod Patel (1221832001)
3) Kenil Vipulkumar Patel (1223049204)

Setup and execution:

* RaspberryPI
- Install appropriate OS to a memory card and attach the memory card to the raspberryPi, create a user and enable remote access rights. 
- Install the Pi camera to the raspberryPi and enable the pi camera options. 
- Install python and required dependencies to the raspberryPi.
- Run multithread.py to perform the above-mentioned operation.

* Docker
- Download the dockerfile and the above-mentioned files along with the other required files to construct the docker image. 
- Using dockerfile, create a container image and push it to the AWS ECR. 

* AWS Resources
- Create S3 buckets, SQS result fetching queue and dynamoDB with having student information. 

* Lambda

- Create and set up Lambda function on AWS using the container image uploaded to AWS ECR. 
- Provide appropriate access rights for AWS resources to interact with each other. 

