# MongoDB
MongoDB is the leading modern, general purpose, document-based, distributed database, designed to unleash the power of software and data for developers and the applications they build.
The [MongoDB Data API ](https://www.mongodb.com/data-api/l) provides you REST access to your data in [MongoDB Atlas ](https://www.mongodb.com/atlas),the database-as-a-service offering by MongoDB. The API includes endpoints that create, read, update, delete, and aggregate documents in your cluster.

## Getting Started
Get started by creating a [MongoDB Atlas Account](https://www.mongodb.com/cloud/atlas/register) with a running Cluster, hosting the Database that you want to connect to from the Power Platform.  

## Supported Operations
Perform CRUD operations and aggregations on your data in minutes

## Authentication
To authorise the request and obtain access to the underlying data, you need to use an API Key. To create an API key, follow the steps provided in the below section

## Pre-requisites for Using the Connector
1. [Enable the Data API](https://www.mongodb.com/docs/atlas/api/data-api/#1.-enable-the-data-api)

The Data API is disabled by default. To use the API, you need to turn it on in the Atlas UI for one or more clusters. Click Data API in the left navigation menu. On the following screen, select one or more clusters that you want to enable the API on from the dropdown menu and then click Enable the Data API.

2. [Create a Data API Key](https://www.mongodb.com/docs/atlas/api/data-api/#2.-create-a-data-api-key)

The Data API uses project-level API keys to manage access and prevent unauthorized requests. Every request must include a valid Data API key.A Data API key grants full read and write access every collection in a cluster and can access any enabled cluster in the project.
Click Create API Key, enter a unique name for the new key, and then click Create API Key.
You can now see and copy your new API key for the first and only time. Once you close the modal, Atlas will never expose the value again.


## Importing the connector

In the Power Automate portal, click on Data -> Custom Connectors in the menu on the left.

<img width="199" alt="Screenshot 2022-05-24 at 6 55 25 PM" src="https://user-images.githubusercontent.com/101181433/170048861-1b6568ca-2159-4cfe-9c27-65b92fa70ce2.png">


Click on + New custom connector in the top right menu and select  "Import from GitHub"

<img width="261" alt="Screenshot 2022-05-24 at 6 54 50 PM" src="https://user-images.githubusercontent.com/101181433/170047186-c2b92de9-6451-43ca-8a28-afa746d855d4.png">


Choose "Certified" radio button , Branch as "master" and choose connector "MongoDB" from the dropdown.

<img width="607" alt="Screenshot 2022-05-24 at 6 57 41 PM" src="https://user-images.githubusercontent.com/101181433/170049206-c2cbb534-d311-4828-a14e-7e143ed76af7.png">
