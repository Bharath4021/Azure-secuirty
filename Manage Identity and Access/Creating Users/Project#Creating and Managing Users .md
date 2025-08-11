# Project : Creating and Managing Users in Entra ID
## Introduction
Entra ID is Microsoft’s cloud-based identity and access management service that enables secure sign-in and access control for users, devices, and applications. In enterprise environments, managing users effectively is critical to ensure the right people have the right access at the right time. This project focuses on creating and managing user accounts in Azure AD—covering manual user creation, bulk import, assigning roles, and updating user information. Mastering this process ensures compliance, security, and operational efficiency for organizations using Azure services.
## Steps to Do
### **Prerequisites**
-  Azure subscription with Global Administrator or User Administrator role.
- Access to the Azure Portal (https://portal.azure.com).
### **Access Azure Entra ID**
- Sign in to Azure Portal.
- In the left-hand navigation pane, click Azure Active Directory.

  ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/6a76f3ecb3fdf7db772abb5383c38352300d38d5/Manage%20Identity%20and%20Access/Creating%20Users/images/Screenshot%20(1134).png)
  
### **Create a New User (Manual Method)**
- Inside Azure AD, select Add → Users → New user → Create new user.

  ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/0a28f4d3a1307ceb8ebd5c6e5a8bc8af883983ce/Manage%20Identity%20and%20Access/Creating%20Users/images/Screenshot%20(733).png)
  ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/0a28f4d3a1307ceb8ebd5c6e5a8bc8af883983ce/Manage%20Identity%20and%20Access/Creating%20Users/images/Screenshot%20(735).png)

#### Fill in required details:
- User name (e.g., sunil@mytrainings4021gmail.com)
- Name (Full display name)
- Password (Auto-generate or custom)

  ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/0a28f4d3a1307ceb8ebd5c6e5a8bc8af883983ce/Manage%20Identity%20and%20Access/Creating%20Users/images/Screenshot%20(751).png)

#### Fill in the user properties (such as job title, department, contact info, etc.):

 ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/0a28f4d3a1307ceb8ebd5c6e5a8bc8af883983ce/Manage%20Identity%20and%20Access/Creating%20Users/images/Screenshot%20(752).png)
 
#### Assign roles if needed:

 ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/0a28f4d3a1307ceb8ebd5c6e5a8bc8af883983ce/Manage%20Identity%20and%20Access/Creating%20Users/images/Screenshot%20(753).png)

- Under Groups and roles, click Add group and select the appropriate group(s) to add the user to

  ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/0a28f4d3a1307ceb8ebd5c6e5a8bc8af883983ce/Manage%20Identity%20and%20Access/Creating%20Users/images/Screenshot%20(754).png)
  
#### Click Create :
 
 ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/0a28f4d3a1307ceb8ebd5c6e5a8bc8af883983ce/Manage%20Identity%20and%20Access/Creating%20Users/images/Screenshot%20(756).png)
### Viewing All Users Created:
In Microsoft Entra ID, I just go to the Users section to see all the accounts I’ve created. I can quickly search for a specific user, click on their name, and then manage their details, change roles, or update their group memberships right from there.

![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/6f0da5afff84c4488d46903511082f5e4929b400/Manage%20Identity%20and%20Access/Creating%20Users/images/Screenshot%20(1135).png)

## Conclusion:
Creating and managing users in Azure Entra ID is a foundational skill for any Azure Security Engineer or IT administrator. By understanding how to create users manually, assign to groups, and manage user properties, you ensure that identity management aligns with both security best practices and business requirements. 
