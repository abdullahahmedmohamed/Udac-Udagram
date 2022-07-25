![AWS_Diagram](./imgs/Udagram.drawio.png)

### RDS

create and deploy a public accessible PostgreSQL Database on cloud

> Amazon Relational Database Service (Amazon RDS) is a collection of managed services that makes it simple to set up, operate, and scale databases in the cloud

### S3

1. First Bucket used as Static Website Hosting to host front-end with public accessibility
1. Second Bucket used as space storage for the back-end application files (this is a private bucket created by Elastic Beanstalk)

> Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance

### Elastic Beanstalk

1. provides nodejs environment with 1 EC2 instance to host back-end application on the cloud
1. provides load balancer to balance the load between instances which will be helpful for the scalability in the future

> AWS Elastic Beanstalk makes it even easier for developers to quickly deploy and manage applications in the AWS Cloud. Developers simply upload their application, and Elastic Beanstalk automatically handles the deployment details of capacity provisioning, load balancing, auto-scaling, and application health monitoring.
