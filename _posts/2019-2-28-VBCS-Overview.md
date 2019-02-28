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
Follow the wizard to display only BookTitle and author. 
No Queries to define-> click save.
This would be the outcome.
##image7

Now let's add an action when somebody clicks on the item on the Listview. We want to someone to see more details about the book ie. Description & Published Dates.
Select on the List view. Click on the data Icon. Then click on the "Add Details Page"
##image8
Select the Business Object on the Wizard.
Drag and drop Booktitle, Description, PublishDate on the "Fields" area.
Click Finish.

You can now test the app by clicking on the Live button. Select a row on the list view.
##image9

Let's add a book! 

Click back to design view and click on the list view to highlight it. Select "Add a create page"

The same steps like above apply -> select the business objects and select the objects to be inputed. 

The finished screen should look like this-> 
##image 10
Click on the play button to test your application!
image 11

Below is a demo video of the application we just created.

##demo video.

You can download the skeleton application i created [here]

If you have any questions regarding VBCS feel free to reach out to me. 

I would love your feedback too, comment below.

Thank you!

*The views expressed in this blog are my own and do not necessarily reflect the views of Oracle Corporation.*






