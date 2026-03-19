# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: Shamrin B
* **Register Number**:212224040306
* **Date of Submission**:19-03-2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)



1.Logged into AWS and launched an EC2 instance using Amazon Linux 2 with a key pair.

2.Configured the security group to allow SSH (22) and database port (3306).

3.Connected to the EC2 instance using SSH from the local system.

4.Installed MySQL server, started the service, and configured root credentials.

5.Created a sample database and table, inserted records, and verified using SQL queries.
---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

(Insert Screenshot Here)

---
<img width="1920" height="1080" alt="Screenshot (71)" src="https://github.com/user-attachments/assets/de838981-1ec2-4184-8a1e-93bd947652ed" />


### Screenshot 2: Database Service Running

(Insert Screenshot Here)


<img width="1920" height="1080" alt="Screenshot (75)" src="https://github.com/user-attachments/assets/24228977-f6f8-46e9-98e4-928f93c49b66" />

---

### Screenshot 3: Sample Database and Table

(Insert Screenshot Here)

<img width="1920" height="1080" alt="Screenshot (74)" src="https://github.com/user-attachments/assets/0322f594-9b79-4b2b-bfa4-3fb17843c734" />

---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
