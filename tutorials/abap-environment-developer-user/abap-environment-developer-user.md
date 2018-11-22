---
auto_validation: true
title: Create a Developer User in SAP Cloud Platform ABAP Environment
description: Create a developer user with the developer role in SAP Cloud Platform ABAP environment.
primary_tag: topic>abap-development
tags: [  tutorial>beginner, topic>abap-development,  products>sap-cloud-platform ]
time: 10
---

## Prerequisites  
- You must have an administrator user.

## Details
### You will learn
- How to create an employee user
- How to assign business roles to an employee user

### Time to Complete
**10 Min**.


---
[ACCORDION-BEGIN [Step 1: ](Log in to SAP Fiori Launchpad as administrator)]
1. Open eclipse and do right click on your system and navigate to **Properties**.
![Open eclipse](Picture17.png)
2. Navigate to **ABAP Development** and copy the **System URL**.
![System URL](Picture18.png)
3. Copy this URL in a browser and change the URL like this:
Add `-web` after `.abap` and `/ui` at the end of URL.
`https://<your-system>.abap-web.eu10.hana.ondemand.com/ui`
![Change URL](Picture20.png)
7. Login with admin user and password in SAP Fiori Launchpad.
![Login to SAP Fiori Launchpad](Picture19.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 2: ](Navigate to Maintain Employees application)]

Navigate to **Maintain Employees** application.
![Maintain Employees](Picture2.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 3: ](Create a new employee)]

Create a new employee by clicking **New**.
![Create a new employee](Picture3.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 4: ](Enter user data)]

1. Enter user data and a valid Email address.
2. **Save** your changes.
![Enter user data](Picture4.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 5: ](Create business user)]

1. Select the newly created entry in the employee list.
2. Press **Create Business User**.
![Create business user](Picture5.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 6: ](Add business roles)]

1. Press **Add** Business Roles.
![Add business Roles](Picture6.png)
2. Select business role **Developer** and press **OK**.
![Add business Roles](Picture7.png)
3. Save all changes with click on **Save**.
![save](Picture8.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 7: ](Test yourself)]
In which application on your SAP Fiori launchpad can you create developer user as an administrator?

[VALIDATE_1]
[ACCORDION-END]
---