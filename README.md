# Node-RED-HERE
In this tutorial, we will be building an application that streams real-time twitter updates on a map using Node-RED, Twitter API and HERE Technologies API.
![image](https://user-images.githubusercontent.com/36239840/91075370-04780200-e64f-11ea-8cd3-cd2f6cfb2bbd.png)
## Prerequisites
- Signup for a <a href="https://bit.ly/HEREDevs">HERE Developer account</a>
- Signup for an <a href="https://ibm.biz/HERETechnologies">IBM Cloud account</a>
- Apply for access to Twitter API by <a href="https://developer.twitter.com/en/apply-for-access">creating Twitter Developer account</a>
- Add the following nodes to your Node-RED palette
  - <a href="https://flows.nodered.org/node/node-red-contrib-web-worldmap">node-red-contrib-web-worldmap</a>
  - <a href="https://flows.nodered.org/node/node-red-contrib-twitter-stream">node-red-contrib-twitter-stream</a>
## Architecutre Diagram
![](https://user-images.githubusercontent.com/36239840/90247623-06b8b000-de48-11ea-9fca-8c698ba98e30.PNG)
## Steps
### <a href="./create-app.md">Step1: Create Node-RED Application</a>
### <a href="./Twitter-HERE.json">Step2: Import the flow</a>
![image](https://user-images.githubusercontent.com/36239840/91162113-b6114480-e6dc-11ea-980c-ed83a803eedc.png)
This flow flows as follows:
1- Streaming Tweets from Twitter API
2- Saving Tweet, Username, and Location into context variables
3- Passing Tweets' Location to HERE Technologies GEO Coding Lookup API
4- Saving the Longitude & Latitude from the GEO Coding API call
5- Printing the details on the world map
## Useful Resources
- <a href="https://developer.ibm.com/">IBM Developer</a>
- <a href="https://developer.ibm.com/components/node-red/"> Node-RED on IBM Developer</a>
- <a href="https://nodered.org/">Node-RED Documentation</a>
- <a href="https://github.com/heremaps/here-sdk-examples">HERE SDK Examples</a>
