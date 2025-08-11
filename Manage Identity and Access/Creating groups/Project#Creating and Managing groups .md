# Project : Creating and Managing Groups in Entra ID
## Introduction:
In Azure Active Directory (Azure AD), groups are used to organize users and simplify access management. Instead of assigning permissions to individual users, administrators can assign them to a group, and all members inherit those permissions.
 **There are two main group types:**
 - **Security Groups** → Control access to resources and applications.
 - **Microsoft 365 Groups** → Enable collaboration through shared resources like Outlook, SharePoint, and Teams.
In this project, we will create both a Security Group and a Microsoft 365 Group, add members to them, and verify their configuration. This is an essential skill for Azure Security Engineers and aligns with AZ-500 exam objectives under Manage Identity and Access.
## Steps to Do
### Step 1 — Create a Security Group
- Sign in to the Azure Portal.
- Navigate to Azure Active Directory → Groups → New Group.
 ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/b501738ae68bf87b5d11e5d0409011a4d5feb9ee/Manage%20Identity%20and%20Access/Creating%20groups/Images/Screenshot%20(1136).png)

- Group type: Select Security.
- Group name: App-Developers.
- Membership type: Assigned.
- Add members (e.g., alice.smith).

 ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/279f2f688de4258992860f200876c07cd7566d6d/Manage%20Identity%20and%20Access/Creating%20groups/Images/Screenshot%20(741).png)

- Click Create.
### Step 2 — Create a Microsoft 365 Group
- In Azure AD → Groups → New Group.
- Group type: Select Microsoft 365.
- Group name: Marketing Team.
- Membership type: Assigned.

 ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/279f2f688de4258992860f200876c07cd7566d6d/Manage%20Identity%20and%20Access/Creating%20groups/Images/Screenshot%20(1138).png)

- Add members (e.g., bob.jones).

 ![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/279f2f688de4258992860f200876c07cd7566d6d/Manage%20Identity%20and%20Access/Creating%20groups/Images/Screenshot%20(1140).png)

- Click Create.

### Step 3 — Viewing All Users Created:
In Microsoft Entra ID, I just go to the Groups section to see all the groups I’ve created. I can quickly search for a specific group, click its name, and manage details, modify members, or adjust assigned roles from there.

![image alt](https://github.com/Bharath4021/Azure-secuirty/blob/279f2f688de4258992860f200876c07cd7566d6d/Manage%20Identity%20and%20Access/Creating%20groups/Images/Screenshot%20(1143).png)

## Conclusion

By completing this project, we successfully created and managed groups in Azure Active Directory. Security Groups help manage resource access efficiently, while Microsoft 365 Groups enable collaboration with shared tools. This foundational skill is vital for effective identity and access management in Azure.