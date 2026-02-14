# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  

<img width="1699" height="893" alt="Screenshot 2026-02-13 083343" src="https://github.com/user-attachments/assets/69dfa875-593c-48b4-8979-4f83102574d2" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group
    
**Screenshot:**

<img width="1590" height="904" alt="Screenshot 2026-02-14 184837" src="https://github.com/user-attachments/assets/8646f356-58a6-46df-a7b4-4f80255374ce" />

<img width="1597" height="906" alt="Screenshot 2026-02-14 184930" src="https://github.com/user-attachments/assets/97fdc304-4880-49ce-96c1-af71403cc35a" />

<img width="1595" height="912" alt="Screenshot 2026-02-14 184945" src="https://github.com/user-attachments/assets/3d4af02b-65bb-4d85-aedf-5296f92d4853" />



### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3
  
**Screenshot:**
 <img width="1588" height="902" alt="Screenshot 2026-02-14 184957" src="https://github.com/user-attachments/assets/6267a5b4-df58-46fb-962d-eaf7249080e6" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** TRISHA PRIYADARSHNI PARIDA

**Course:** Introduction to Cloud Computing  

