
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
   - ![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/52548f56-70da-4332-b6cf-a1a65ef87174)


3. **Create New Service Connection:**
   - Click on the `+ New service connection` button.


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/590b0c9f-b94e-48c6-bf81-3c2239c6ca92)


4. **Choose Service Connection Type:**
   - Select the type as "AWS."
![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/868c942e-d288-429d-8699-c1e466a110dc)

5. **Provide AWS Connection Details:**
   - Enter the AWS access key and secret key in the appropriate fields.
   - Optionally, specify a session token if you're using temporary security credentials.

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/04cce22b-0640-4797-ab1f-af282cd0f5e7)

6. **Name the Connection:**
   - Give your service connection a name like "AWS"
  
   - ![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a57583d4-4908-47ce-93fe-c9529d03af60)


7. **Description (Optional):**
   - Optionally, you can add a description if you choose.

8. **Save the AWS Service Connection:**
   - Click on the `Save` button to create the AWS service connection.
![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/8a11bded-adfc-452a-a693-28c424873ef6)





![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a4d6fda1-c334-4822-aecf-c7917e4f181c)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/d156de18-823c-4678-befc-10291f53bf45)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/418a3b8f-e4e9-49c6-90a5-be9c10efb66a)





![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/5b77a334-4540-484f-8d71-eed37091807d)
![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/74108f08-e5ab-498e-b3f8-219f41d72272)
![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/9786b89d-fbe4-454a-a47c-7236feb87636)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/3eb243c1-0655-42af-95ef-5e7edcb28748)
![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/8d2110ce-5689-4124-8887-867947ceba6a)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/44d9aef5-b5ac-43ed-9f4c-89a63c32010b)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/6682124b-76c9-4317-9c88-9dbceae24a7c)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/7df24d3e-88b3-4537-9c26-59104aca706d)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/299a69da-abc5-4d66-bf88-44cb1fd43c1e)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/beaeb602-078c-4249-8a45-584417faede0)
![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a0117f34-85bb-4657-b56d-5456a1685992)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/f66760da-cf34-4104-99b0-c739cc71d966)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/e92af746-90f1-4d25-86a1-d0bef65babc6)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/5ec2a8c9-481a-4288-8876-44af1b58daee)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/72378106-ee40-42c8-a0e7-f570da8099ef)


### Step-by-Step Guide: Creating a Service Connection in Azure DevOps

#### Part 1: Create a Service Connection

1. **Navigate to Project Settings:**
   - Open your Azure DevOps organization.
   - Go to the project for which you want to create a service connection.
   - Click on "Project settings" in the bottom left corner.

2. **Access Service Connections:**
   - Under the "Pipelines" category, click on "Service connections."
  
     ![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/87c4002f-1815-4b98-8dad-b58ff6563947)


3. **Create New Service Connection:**
   - Click on the `+ New service connection` button.

4. **Choose Service Connection Type:**
   - Select the type of service connection based on the external service you are connecting to (e.g., Azure Resource Manager, GitHub, Docker Registry, etc.).




### Configure AWS for Terraform as a Service Provider in Azure DevOps

#### Part 1: AWS for Terraform Service Connection


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/c2c9865a-9b72-4d22-8f6b-5b368299b403)




![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/fbea8d76-0e02-497c-8e56-b338b8ac79ec)


### Configure Snyk as a Service Provider in Azure DevOps


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/5c7215d1-bf8d-4536-b41b-79649123c357)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/fcb8d631-ec3e-4599-9743-a8dd73e839e2)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a6843f81-f1c0-4185-97fc-cc8d888eac8b)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/1747ebcb-022c-49bc-88b4-3cb8e2aae977)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/1efa93cf-2da7-4b19-b869-2a5f5bb9ab35)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/68f102d7-6f25-4556-b2d0-c97fbd3fe687)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/63686638-e779-44cf-a347-94ff1d6423ea)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/ae113fe8-b651-44c4-be8a-ac8d6a3084b6)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a0608c5e-e569-444d-b08a-6c6589c8ed1f)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/4c67263d-c92b-4c31-b5ba-3cd31522532f)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/ce9cbf55-9f1d-4583-b664-fdcb33e38c86)


### Create an S3 bucket in AWS

## Step 1: Create an S3 Bucket

1. In the AWS Management Console, navigate to the **S3 service**.

2. Click on the **Create bucket** button.

3. Provide a globally unique name for your bucket. AWS S3 bucket names must be unique across all regions and AWS accounts. Choose a name that reflects your project or organization.

4. Choose the region where you want to create the bucket. Select a region that is geographically closer to your users or resources.

5. You can leave other settings as default for now, or configure them based on your specific requirements. Click **Next** until you reach the **Review** step.

6. Review your settings, and if everything looks good, click **Create bucket**.



## Note: Obtain S3 Bucket Name
### Make a note of the S3 bucket name you just created. You'll need this information when configuring Azure DevOps.

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/aba2a94a-17ee-4513-95e7-3effbf9c42d8)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/47306de9-9b99-4f8f-8f30-c682761a1d76)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a9805d0b-27a0-4231-be03-eebb717a8f3f)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/f9286580-8714-4400-972b-85ddd26f83cd)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/d5a6c8e8-6059-4353-9cd6-83e4e28b0433)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/ac909110-b971-4b8d-9d57-f576ebe9d75a)

## Create a Folder Within the S3 Bucket

1. In the AWS Management Console, navigate to the **S3 service**.

2. Click on the S3 bucket you created earlier.

3. Inside the bucket, click on the **Create folder** button.

4. Provide a name for the folder, for example, `terraform-statefiles`. This folder will be used to organize your Terraform state files.

5. Click **Save** or **Create folder**

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/4c690a35-a82b-437f-ac0a-4ef2e9a36f03)

 ![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/fb5a96c1-a991-485b-b5e2-1e6b8dc641ed)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/eac9136b-ab2a-44af-aaa6-a974b71e6e7d)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a87d4198-e0c2-4c27-bc45-78167dbad15b)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/c12be2a0-241f-42b5-8860-d60e37fe522d)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/33cde515-574b-45f0-a89c-2d852ac8434d)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/f46e5fd1-b11a-432c-8a48-6b7044e51259)bucket


5. Obtain arn: and save in notepad application

6. paste your arn in the console:

7. ![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a7e955e2-6914-492f-856d-55b2d27ffc1d)



## Pipelines and Releases
## Concept of a Release in Azure DevOps (ADO)

In Azure DevOps (ADO), a "release" refers to the process of deploying and delivering software or application changes to a specific environment, such as staging or production. The release management process in Azure DevOps helps automate and streamline the deployment of your application through different stages or environments, ensuring consistency and reliability in the deployment process.

### Key Concepts:

1. **Release Pipeline:**
   - A release pipeline is a series of connected, automated steps that define the path to deploy an application from source code to a target environment.
   - It typically includes stages representing different environments (e.g., Dev, QA, Staging, Production) through which the application progresses.

2. **Artifacts:**
   - Artifacts are the build outputs or packages that are generated by your build pipeline. These artifacts are used as the input for the release pipeline.
   - Examples of artifacts include compiled binaries, executables, or any other files needed for deployment.

3. **Environments:**
   - Environments represent the target infrastructure where your application will be deployed. Common environments include development, testing, staging, and production.
   - Each environment in a release pipeline can have specific configurations and approval gates before the deployment proceeds.

4. **Approvals:**
   - Release approvals allow you to control and manage the deployment process. Before a release moves to the next stage, it can require manual approval from designated stakeholders.
   - This ensures that critical changes are reviewed and approved before reaching production.

5. **Gates:**
   - Gates are conditions or criteria that must be met before a release can progress to the next stage. These can include automated tests, monitoring conditions, or external approvals.
   - Gates help ensure the quality and reliability of the release.

6. **Release Triggers:**
   - Release triggers define the conditions under which a release should be initiated. Common triggers include continuous deployment triggered by a successful build or manual initiation.

7. **Release Artifacts:**
   - Release artifacts are the deployment packages produced by a release pipeline. These packages are deployed to the specified environments during the release process.

8. **Logs and History:**
   - ADO provides detailed logs and a release history, allowing you to track the progress of each release, view deployment logs, and troubleshoot any issues that may arise.

By using release pipelines in Azure DevOps, development teams can automate and standardize the deployment process, reducing manual errors, ensuring consistency across environments, and accelerating the delivery of software changes to end-users.


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/c89b7554-e084-401e-88c9-a1582305d0e6)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/8c14a0c2-3fd5-46bb-a7d7-294bb5b064cc)




![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/295050fc-92b8-4067-9f60-bd638bc866ba)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/1b7545c5-aa86-44a5-99e2-263dd50367b8)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/568c75f4-1e69-4df0-8641-aeba2be2ed2e)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/3062a696-0795-411f-b5bb-5d8845e20bbe)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/336b5dda-5dce-4d6e-94a4-f838c9743a3b)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/0a39200f-484b-411a-8846-2e408877d4ed)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/88d416ed-fa34-49d2-986a-a8f1a3cb16a8)



![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/a0877d23-b5d3-4bb6-8d7e-c58ea8f07585)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/bcec95e6-e04f-4a98-bc33-ab04207b19b8)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/67932b41-be54-4f58-b007-c1414b754310)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/c9ebccaf-3ba6-44d6-a3fd-297f6883f3d1)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/e8b8396a-7e17-43ec-8330-d62a2d5c7386)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/2cd112e3-5a30-427d-9c2b-88bbb3f91163)


![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/4db29377-748a-4223-bc72-b664c44b78a5)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/4ef5f2fe-cb4a-4e66-b9dd-320075870dff)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/518c9089-043c-467f-b655-2763fd8a878e)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/0d3ef1b9-07cc-49c9-9377-bf46093b6cf5)

![image](https://github.com/mindmotivate/ADO_Piplines/assets/130941970/5ec8a784-a19c-4d3a-8d46-29fa35589328)

