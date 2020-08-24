# Node-RED-HERE
In this tutorial, we will be building an application that streams real-time twitter updates on a map using Node-RED, Twitter API and HERE Technologies API.
![image](https://user-images.githubusercontent.com/36239840/91075370-04780200-e64f-11ea-8cd3-cd2f6cfb2bbd.png)
## Prerequisites
- <a href="https://bit.ly/HEREDevs">Signup for a HERE Developer account</a>
- <a href="https://ibm.biz/HERETechnologies">Signup for an IBM Cloud account</a>
- <a href="https://developer.twitter.com/en/apply-for-access">Apply for access to Twitter API by creating Twitter Developer account</a>
- Add the following nodes to your Node-RED palette
  - <a href="https://flows.nodered.org/node/node-red-contrib-web-worldmap">node-red-contrib-web-worldmap</a>
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
- Deploying the application will take few minutes, after it's done deploying you will notice the application details have been updated and now you can access the Node-RED Application from App URL.
![image](https://user-images.githubusercontent.com/36239840/90339873-19c4af00-e005-11ea-9471-f843c5426e46.PNG)
- When you click on the click, you will be prompted to configure your Node-RED application. Once you are done, you will be redirected to a new page, click on "Go to your Node-RED flow editor"
![image](https://user-images.githubusercontent.com/36239840/90340002-12ea6c00-e006-11ea-97b3-61c002678e9c.png)
- Congratulations! you made it! :D
![image](https://user-images.githubusercontent.com/36239840/90339878-1b8e7280-e005-11ea-9b0e-b53b434698fc.PNG)

