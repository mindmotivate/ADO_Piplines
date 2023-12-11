
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



