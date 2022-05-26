# MongoDB
MongoDB is the leading modern, general purpose, document-based, distributed database, designed to unleash the power of software and data for developers and the applications they build.
The [MongoDB Data API ](https://www.mongodb.com/data-api/l) provides you REST access to your data in [MongoDB Atlas ](https://www.mongodb.com/atlas),the database-as-a-service offering by MongoDB. The API includes endpoints that create, read, update, delete, and aggregate documents in your cluster.

## Getting Started
Get started by creating a [MongoDB Atlas Account](https://www.mongodb.com/cloud/atlas/register) with a running Cluster, hosting the Database that you want to connect to from the Power Platform.  

## Supported Operations
Perform CRUD operations and aggregations on your data in minutes. Read the full documentation of the operations and their examples [here](https://www.mongodb.com/docs/atlas/api/data-api-resources/#data-api-resources)

## Authentication
To authorise the request and obtain access to the underlying data, you need to use an API Key. To create an API key, follow the steps provided in the below section

## Prerequisites for Using the Connector
1. [Enable the Data API](https://www.mongodb.com/docs/atlas/api/data-api/#1.-enable-the-data-api)

2. [Create a Data API Key](https://www.mongodb.com/docs/atlas/api/data-api/#2.-create-a-data-api-key)

## Importing the connector

In the Power Automate portal, click on Data -> Custom Connectors in the menu on the left.

<img width="199" alt="Screenshot 2022-05-24 at 6 55 25 PM" src="https://user-images.githubusercontent.com/101181433/170048861-1b6568ca-2159-4cfe-9c27-65b92fa70ce2.png">


Click on + New custom connector in the top right menu and select  "Import from GitHub"

<img width="261" alt="Screenshot 2022-05-24 at 6 54 50 PM" src="https://user-images.githubusercontent.com/101181433/170047186-c2b92de9-6451-43ca-8a28-afa746d855d4.png">


Choose "Certified" radio button , Branch as "master" and choose connector "MongoDB" from the dropdown.

<img width="607" alt="Screenshot 2022-05-24 at 6 57 41 PM" src="https://user-images.githubusercontent.com/101181433/170049206-c2cbb534-d311-4828-a14e-7e143ed76af7.png">

## Changes required in the Connector
1. In the Base URL field in the General tab, replace the placeholder **"_Data API App ID_"** with the App ID from the URL endpoint under **Data API** tab in Atlas.  
2. For some APIs whcih expect a Json response , the layout/sample of the json needs to be added using the **"Import from Sample"** option for the Response under the **Definition** tab.

## Known Limitations

1. Data API logs all requests and stores the logs for 30 days.They can be viewed from the **Data API** screen in the **Logs** tab
2. The Data API has restrictions in terms of the size of the Request and the Response body and the response time which is detailed [here](https://www.mongodb.com/docs/atlas/api/data-api/#request-limitations)

