# AWS Employee Management System

## Project Overview
This project demonstrates how Amazon EC2 can host an application that connects to Amazon RDS for MySQL to store and manage employee records.

## Objectives
- Understand AWS EC2 and RDS integration.
- Create and configure a MySQL database.
- Learn secure database connectivity using VPCs and security groups.
- Document the architecture and deployment process.

## AWS Services
- **Amazon EC2:** Application hosting.
- **Amazon RDS for MySQL:** Relational database.
- **Amazon VPC:** Network isolation.
- **Security Groups:** Control network traffic.
- **AWS IAM:** Manage permissions where required.

## Architecture
Application/User → EC2 Application Server → RDS MySQL Database

Additional AWS services will be documented as they are configured and tested.

## Implementation Steps
1. Create the AWS network and required security groups.
2. Launch an EC2 instance.
3. Create an Amazon RDS MySQL database.
4. Configure secure connectivity between EC2 and RDS.
5. Create an employee database and table.
6. Test database connectivity and employee record operations.
7. Document screenshots and results.

## Security Considerations
- Keep the database private.
- Allow database access only from authorized application resources.
- Never publish database passwords, access keys, or other secrets.
- Do not expose employee personal information.

## Project Status
Update this section as each component is implemented and tested.

## Learning Outcomes
This project helps demonstrate foundational AWS networking, compute, relational database, and security concepts.