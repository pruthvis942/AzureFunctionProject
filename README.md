
# Azure MVC Web Application with Functions and Blob Storage

This repository showcases a .NET MVC web application integrated with Azure services. The main functionalities include uploading requests to an Azure Queue through an Azure HTTP function, processing the requests with a Blob Trigger function, and updating an Azure SQL database. Additionally, the project supports image uploads to Azure Blob Storage, image resizing with a Blob Trigger function, and an Azure Timer Trigger function for periodic tasks such as sending email notifications using SendGrid. CRUD operations are exposed through a REST API using Azure HTTP triggers.


## Tech Stack Used

**Main Application:** .NET MVC Web Application

**Azure Services:** 
Azure Functions,
Azure Queue,
Azure SQL Database,
Azure Blob Storage.

**Azure Functions:** Azure HTTP Function,
Azure Blob Trigger Function,
Azure Timer Trigger Function.

**Email Service:** SendGrid for email notifications



## Features

- **Azure Queue Integration:** Upload requests from the MVC web application.
    Azure HTTP function processes requests and adds them to an Azure Queue.

- **Azure SQL Database:** Processed requests are written to an Azure SQL database using a Blob Trigger function.

- **Azure Blob Storage** Upload images through the MVC web application.
    Blob Trigger function resizes uploaded images and updates database status.

- **Azure Timer Trigger Function:** Runs every five minutes and    Sends email notifications for completed tasks using SendGrid. 

- **REST API:** CRUD operations using Azure HTTP triggers. 


## Application Flow

![image](https://github.com/pruthvis942/AzureFunctionProject/assets/154806202/c48162f1-939d-47ab-80d4-475c83be5b05)

## Screenshots

![image](https://github.com/pruthvis942/AzureFunctionProject/assets/154806202/a3445642-ae6b-4922-9be2-552bc12a76de)
![image](https://github.com/pruthvis942/AzureFunctionProject/assets/154806202/f8e45f97-4a78-4c0c-9e60-8acf77338806)
![image](https://github.com/pruthvis942/AzureFunctionProject/assets/154806202/5e9d2cdd-1831-419d-a33d-8f7763408ec6)

