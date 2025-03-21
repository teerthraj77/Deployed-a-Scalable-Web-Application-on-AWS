# Deployed-a-Scalable-Web-Application-on-AWS
Deployed a Scalable Web Application on AWS

Description: Designed and deployed a scalable web application architecture on AWS, transitioning from a traditional monolithic setup to a cloud-native solution.

Key Contributions:

Infrastructure Setup: Configured and deployed an Application Load Balancer (ALB) to handle incoming HTTPS traffic.
Auto Scaling: Implemented an Auto Scaling Group for Tomcat instances, ensuring high availability.
Security & Networking: Defined Security Groups and IAM policies for access control.
DNS Management: Configured Amazon Route 53 for domain name resolution and private DNS zones.
Caching & Message Queue: Integrated Memcached for caching and RabbitMQ for message brokering.
Database Management: Hosted a MySQL instance with security best practices.
Artifact Management: Utilized Amazon S3 for storing build artifacts and static assets.
Automation: Used Bash scripts to automate EC2 instance provisioning and application deployment.
SSL & HTTPS: Configured SSL certificates via AWS Certificate Manager for secure communications.
DNS Mapping: Mapped ELB endpoints to domain names via GoDaddy DNS.
Tech Stack: AWS (EC2, S3, ALB, Route 53, IAM, Auto Scaling, RDS), Tomcat, Memcached, RabbitMQ, MySQL, Bash Scripting, Security Groups, DNS Management.

![aws stack 1](https://github.com/user-attachments/assets/4a22a4e1-8e89-4884-9f1d-3436502e05b5)


# Prerequisites
#
- JDK 11 
- Maven 3 
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


