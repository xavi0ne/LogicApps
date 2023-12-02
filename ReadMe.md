# Secure File Transfer using Azure Logic Apps

## Learn how to build Azure Logic Apps to automate document processing and data operations in a secure by design approach. 

### Pre-requisites

+ An Azure subscription.
+ An M365 subscription.
+ An Azure Storage Account deployed with private endpoint connectivity.
+ A Key Vault resource deployed with private endpoint and RBAC access configured. 
+ An Azure Logic App deployed (consumption) with system assigned managed identity enabled and the following RBAC roles assigned:
    + Storage Blob Data Contributor scoped at storage resource.
    + Key Vault Secrets User scoped at key vault resource. 
+ A SharePoint site configured with an active user account.

## Intended Outcome

Build an Azure Logic App that will automate data processing for structured JSON files and parse JSON objects in a workflow that triggers when a file is uploaded in Azure Storage
and results in the desired JSON objects to securely transfer to a SharePoint list. This demo will provide proficiency in the workflows Azure Logic Apps is capable of performing, reducing the burden of manual labor
involving data by integrating a automation processing. 

## How to begin

Ensure all pre-requisites are met prior to starting the lab. Follow the 'Logic App Secure File Transfer Demo' Word document to start building the Logic App workflow.
