
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
