---
title: "Get started with Migration Manager (Preview)"
ms.reviewer: 
ms.author: jhendr
author: JoanneHendrickson
manager: pamgreen
audience: ITPro
ms.topic: article
ms.service: sharepoint-online
localization_priority: Priority
ms.collection: 
- M365-collaboration
- IT_Sharepoint_Server_Top
- SPMigration
search.appverid: MET150
description: Get started with Migration Manager
---

# Get started with the Migration Manager

Migrating content to the cloud is a time and resource intensive process and normally involves scaling up resources to accommodate the large volume of content that you are moving. This comes at a high operational cost of individually managing each migration machine and the migrations tasks that are running on it. Plus you aren't able to automatically load balance your jobs, or view at a glance the progress and status of your migration tasks across all your machines.

Migration Manager answers those challenges by providing you a centralized way of connecting migration machines (clients), creating tasks, and automatically load balancing your migration tasks across different clients.  

Located in the modern SharePoint admin center, the Migration Manager guides you through the setup of your clients and the creation of your tasks.  You can specify global or task level settings, view all-up task progress, and download aggregated summary reports and detailed task-level reports.

### How does it work? 

It works in three simple steps – connect, create and migrate.

- **Connect**. Connect your computer or VM to the Migration Manager by installing a client on one or more machines

- **Create**. Create a task by entering the URL of the network file share that you want to migrate (your source) and URL of the SharePoint site where you are migrating to (your destination) 

- **Migrate**.  After you click Migrate, Migration Manager does the rest. However many tasks you create, Migration Manager will automatically distribute the tasks across all the connected clients, and you can view the progress, what VM or computer it is running on, and download reports after they complete.


## How do I get started? 

To get started, make sure you have:
 
- **Access to the destination**: You must be either a global admin or SharePoint Online admin to the Office 365 tenant where you want to migrate your content.

- **Access to the source**: Windows credentials that have read access to any of the network file shares you plan to migrate 

- **Computer or VM** that has the necessary prerequisites installed:  See here for the [List of prerequisites](mo-setup-clients.md)  


### Related links

[How to set up multiple clients in Migration Manager](mo-setup-clients.md)</br>
[Migration Manager settings](mo-settings.md)</br>
[How to format your json or csv file for bulk upload into the Migration Manager](mo-bulk-upload-format.md)</br>
