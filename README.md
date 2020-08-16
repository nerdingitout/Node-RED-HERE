# Node-RED-HERE

## Architecutre Diagram
![](https://user-images.githubusercontent.com/36239840/90247623-06b8b000-de48-11ea-9fca-8c698ba98e30.PNG)
### Step1: Create Node-RED Application
- Create a Node-RED application from the catalog. First you will be prompted to give it a name and link it to a Cloudant instance. 
![image](https://user-images.githubusercontent.com/36239840/90339296-f1d34c80-e000-11ea-87b7-44652a0b023f.png)
- If you already have a Cloudant DB you can link it from the drop down menu or create a new instance
![image](https://user-images.githubusercontent.com/36239840/90339304-fc8de180-e000-11ea-9797-ca54d88f86df.png)
- Then you will be redirected to an overview page of the application. In order to use the application, you will need to deploy it on Cloud Foundry. To do so, click on "Deploy your app" button.
![image](https://user-images.githubusercontent.com/36239840/90339531-5511ae80-e002-11ea-99d3-109918cde3fd.PNG)
- The Node-RED Starter kit only supports deployment to the Cloud Foundry space of IBM Cloud. Select the region to deploy your application to. This should match the region you created your Cloudant instance in. Lite users might only be able to deploy to your default region. Click Next to continue.
![image](https://user-images.githubusercontent.com/36239840/90339533-56db7200-e002-11ea-9b78-75964d49a08b.PNG)
- Configure the DevOps toolchain by selecting the region it should be created in – again, try to match the region you selected previously. Click Create. This will take you back to the application details page.
![image](https://user-images.githubusercontent.com/36239840/90339534-593dcc00-e002-11ea-8851-f76cc5d8235f.PNG)
