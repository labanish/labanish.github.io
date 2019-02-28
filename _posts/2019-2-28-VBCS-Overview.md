---
layout: post
title: Oracle Visual Builder Cloud Service
---

You can easily create web and mobile applications via an intuitive drag and drop interface using Oracle VBCS. You can counter the IT backlog on the fast and increasing demands of mordern business by quickly building an departmental mobile or web application.

You don't need to install any software development tools-With the Oracle Visual builder Cloud Service or Oracle Intergration Cloud Service you are good to go!. 
VBCS leverages the low code development approach. 

**I will walk you through how to create a simple VBCS mobile application. **

I have been reading alot of late, thus i will create a simple book tracking system. We shall leverage on Data from a csv file.

Log in to your [Oracle Cloud Account.](https://cloud.oracle.com/home)
Go to the Visiual builder Cloud service or Oracle Integration Cloud and select Visual Builder.
Create new application.

########Image1

Your landing page looks like this. 

###image3

Select Mobile application and give it a name.

We first need to create a Business Object. In my case we shall import data from a csv file. This also could be a service connection to a REST API.
On the left most menu of the window. Select Business Objects then click on the hamburger menu and select data manager. 

##Image5
Import the BooksCatalog.csv

Go back to the building interface. 

Drag and drop a ListView from the Components pallet. 

Click on Add Data.
Select the Business Object you created (BooksCatalog) 
Follow the wizard to display only BookTitle, Author Publish Date.




