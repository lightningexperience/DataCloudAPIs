# DataCloudAPIs

I The  Data Cloud (fka CDP) Postman collection is a great starting point for exploring Salesforce Data Cloud APIs. However some of the auhentication steps are abstracted and the steps  that I need to do was not immediately evident.  I tested the following steps to examine the differences in the two types of Data Cloud APIs - Direct API and Connect API.

Salesforce Data Cloud (fka Salesforce CDP) provides two different kinds of APIs to access its data: Connect API and Direct API.
Direct APIs are faster and are documented in the Data Cloud Developer Guide. If we are building use cases such that Data Cloud data needs to be surfaced in real-time (e.g., UI displaying data fetched from Data Cloud in real-time) then direct API may be a good option.

The Direct APIs need to be authenticated with in several steps as explained in the Data Cloud Developer documentation.

Connect APIs have a simpler authentication process – we simply authenticate with the Data Cloud home org. However the Connect APIs are not as expected to be as fast as Direct APIs so it may not be the best choice for real-time UI based integration (e.g., display data fetched directly from Data Cloud in the UI). 

I have documented the detailed step by step method I used to retrieve data from Data Cloud using both Direct API and Connect API: <a href="https://www.appcloud101.com/working-with-salesforce-data-cloud-apis/"> <strong> Working with Salesforce Data Cloud APIs</strong> </a> 

A note of caution: Please use the Salesforce official documentation for your projects.



