
# Disclaimer: Attention Azure DevOps Users

If you are encountering the following error in your Azure subscription and Organization:

````
(1 error)
(No hosted parallelism has been purchased or granted. To request a free parallelism grant, please fill out the following form https://aka.ms/azpipelines-parallelism-request)

````


Please take the following steps before initiating a new project in Azure DevOps. Special thanks to Ean Thompson for his valuable research on this topic.

## Resolution Steps:

1. Click on your Organization directory.

2. Select the Organization under which the project will be deployed.

3. Open Organization Settings, and under Pipelines, select "Parallel Jobs."

   - This page displays your subscription allotments. If there are 0 allotments for Microsoft-hosted Public or Private parallel jobs, you will encounter an error in your pipeline.

   - To troubleshoot, consider creating another Organization and checking the Parallel job allotments. In some cases, a second organization may allow up to 1800 minutes free. You can then build your pipeline in the organization with available allotments.

   - If the issue persists, check your subscription and request an allotment increase. Alternatively, fill out the error message form to request a free parallel job allotment.

Please be aware that the error may stem from the absence of granted parallelism, and the suggested steps aim to resolve this issue. If further assistance is required, feel free to consult Azure DevOps support or refer to additional resources in the Azure DevOps documentation.



![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/ef139930-ea1b-4c89-9819-43df5f7fdd2a)


# Logging into BalericaDevOps - Quick Start Guide

Welcome to BalericaDevOps! Below are the initial steps to log in, with emphasis on using an "InPrivate" window for Microsoft Edge users. Please follow these instructions carefully.

## Prerequisites:
- Ensure you have a BalericaDevOps email address ending with "@BalericaDevOps.com."

## Steps:

1. Open your web browser and navigate to the official Azure DevOps website using the following URL: [https://azure.microsoft.com/en-us/products/devops/](https://azure.microsoft.com/en-us/products/devops/).

2. Click on the "Sign in" button located in the top right corner of the page.

3. On the sign-in page, enter your BalericaDevOps email address in the provided field.

4. **Important: Use an "InPrivate" window (for Microsoft Edge users) for enhanced security.**

   - If you are using Microsoft Edge:
     - Open a new window.
     - Click on the three dots in the top-right corner.
     - Select "New InPrivate window."

   - If you are using a different browser, consider using its private or incognito mode.

5. Enter your password and click on the "Sign in" button.

6. In the event that you encounter any issues logging in or need an immediate password reset, please contact Theo Waf for assistance.

   - **Theo Waf Contact Information:**
     - Email: theowaf@gmail.com
       
Please note that for security reasons, it is crucial to use an "InPrivate" window and to contact Theo Waf promptly if you face any login difficulties. Thank you for your attention, and enjoy using BalericaDevOps!








# Setting Up IAM User Group and User in AWS Console

## Step 1: Create IAM User Group "ADO"

1. Log in to your AWS Management Console.

2. Navigate to the "IAM" (Identity and Access Management) service.

3. Click on "Groups" in the left navigation pane and then click "Create New Group."

4. Enter the Group Name as "ADO" and click "Next Step."

5. Attach the policy "AdministratorAccess" to grant administrator permissions. Click "Next Step."

6. Review the group information and click "Create Group."

## Step 2: Create IAM User "ADO" and Add to Group

1. In the IAM dashboard, click on "Users" in the left navigation pane.

2. Click "Add user."

3. Enter the User name as "ADO."

4. Select access type:
   - For "Console password," choose "Autogenerated password" or set a custom password.
   - For "Programmatic access," check the box.

5. Click "Next: Permissions."

6. Choose "Add user to group" and select the "ADO" group.

7. Click "Next: Tags" and add tags if needed.

8. Click "Next: Review" and review user information.

9. Click "Create user."

10. Note the "Sign-in URL," "User name," and "Password" from the success page.

## Step 3: Obtain Access and Secret Keys

1. On the user creation success page, click "Show" under "Secret access key" and note the key.

2. Click "Download .csv" to download a CSV file containing access key ID and secret access key.

## Step 4: Configure Security Credentials

1. Navigate to the "Users" section in IAM.

2. Click on the "Security credentials" tab for the "ADO" user.

3. Under "Access keys," click "Create access key" if not done. Note the access key ID and secret access key.<>
## ***Don't loose these!!!***

## Step 5: Access AWS Console

1. Open a new browser window and navigate to the AWS Management Console login page.

2. Enter the "Sign-in URL" noted earlier.

3. Enter the "User name" and "Password" created for the "ADO" user.

4. Click "Sign in."

Ensure secure storage and management of login credentials and keys.





![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/447025c8-9128-45be-907a-8be410c9bb19)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/9c0625f3-bc3a-478f-97c8-4abe000ea486)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/eb222e68-43e3-406e-b497-4abc604a8d9d)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/f956b5bb-d1a3-4692-8390-74a95e04837c)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/180b5ac8-da0b-45d6-ae1e-29255ec08c13)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/ad22cc91-e086-4a59-9ed4-b4525c0b993a)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/f082da01-eae6-48a9-b4a5-4b575fa53fe1)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/6523e21c-27aa-416a-ae69-3c286a3d7dad)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/9563bde0-9eb0-4559-8846-9d5fdc72610b)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/4a47cd85-ea28-4e9f-ae57-eb38bb580bc6)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/025a7bfb-d9cc-41ce-9f7c-3db60fd02a39)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a8f84e0a-0765-40f2-b90b-e4fd08b62c00)










![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/ecd80404-a24d-4f47-810f-dd28b7f4c26c)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/d012fff0-a0b1-4c5c-804e-3982eac4b030)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/d8231494-affe-4ccd-a028-b0b1d45ddcfb)




<img width="485" alt="ADOExtentions1" src="https://github.com/mindmotivate/ADO_Piplines/assets/130941970/42c24238-cacf-43f4-be28-8960f919cb83">
<img width="522" alt="ADOExtentions2" src="https://github.com/mindmotivate/ADO_Piplines/assets/130941970/6f06937c-c198-4fe1-b273-6de3c8164153">


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/96bfd63e-b557-4161-bedc-4837f259363b)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/b23b501e-81f9-468d-84c3-ae9fb9095eb1)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/2fd77490-efb5-447c-9b98-9d93cea7c3b6)




# Pipleline Settings

## Change Defaults
By default, the option **"Disable creation of classic release pipelines"** is set to **"disabled."** Unfortunately, this default setting can be frustrating for users who require classic release pipelines. The same default setting also applies to classic build pipelines.

## Action Required
To address this issue and ensure the smooth functioning of your pipelines, it is imperative that you navigate to the organization settings in Azure DevOps and make the necessary changes. Please follow the steps below:

1. **Go to Organization Settings:**
   - Log in to your Azure DevOps account.
   - Navigate to the organization you are working on.

2. **Choose Pipelines:**
   - Within the organization settings, select the "Pipelines" option.

3. **Modify Default Settings:**
   - Look for the option **"Disable creation of classic release pipelines."**
   - Change the setting to **"enabled"** to allow the creation of classic release pipelines.

4. **Verify Classic Build Pipelines:**
   - Look for the option **"Disable creation of classic build pipelines."**
   - Change the setting to **"enabled"** to allow the creation of classic build pipelines.
 
## Why is This Important?
Adjusting these settings is crucial to ensure that you have the flexibility to work with classic release pipelines and classic build pipelines as needed for your projects. Failing to make these adjustments may lead to unnecessary challenges in your DevOps workflows.

## ***Make these changes at your earliest convenience to avoid any disruptions in your projects.***


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a7ffdf41-a05f-43e2-bcc3-72c12cf94d6f)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/759607f5-0cbf-4d23-91ee-46bbfdfb1f69)



5. **Additionally: Disable Triggers for Pull Requests:**
   - Ensure that triggers for building pull requests are turned off to fully implement the selected option. This step is crucial to align with your project's guidelines and control how your pipelines handle pull requests from forked repositories.

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/2d5ebe5c-8f35-4d31-8f10-7772754776cf)






### Configure AWS as a Service Provider in Azure DevOps

#### Part 1: Create an AWS Service Connection

1. **Navigate to Project Settings:**
   - Open your Azure DevOps organization.
   - Go to the project where you want to configure AWS as a service provider.
   - Click on "Project settings" in the bottom left corner.

2. **Access Service Connections:**
   - Under the "Pipelines" category, click on "Service connections."

3. **Create New Service Connection:**
   - Click on the `+ New service connection` button.

4. **Choose Service Connection Type:**
   - Select the type as "AWS."

5. **Provide AWS Connection Details:**
   - Enter the AWS access key and secret key in the appropriate fields.
   - Optionally, specify a session token if you're using temporary security credentials.

6. **Name the Connection:**
   - Give your service connection a name like "AWS Connection."

7. **Test Connection (Optional):**
   - Optionally, you can test the connection to ensure that the provided details are correct.

8. **Save the AWS Service Connection:**
   - Click on the `Save` button to create the AWS service connection.








### Step-by-Step Guide: Creating a Service Connection in Azure DevOps

#### Part 1: Create a Service Connection

1. **Navigate to Project Settings:**
   - Open your Azure DevOps organization.
   - Go to the project for which you want to create a service connection.
   - Click on "Project settings" in the bottom left corner.

2. **Access Service Connections:**
   - Under the "Pipelines" category, click on "Service connections."

3. **Create New Service Connection:**
   - Click on the `+ New service connection` button.

4. **Choose Service Connection Type:**
   - Select the type of service connection based on the external service you are connecting to (e.g., Azure Resource Manager, GitHub, Docker Registry, etc.).




![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/fbea8d76-0e02-497c-8e56-b338b8ac79ec)

