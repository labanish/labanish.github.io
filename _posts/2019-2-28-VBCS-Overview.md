---
layout: post
title: Oracle Visual Builder Cloud Service
---
*I will show you how to create a simple VBCS mobile application*

You can easily create web and mobile applications via an intuitive drag and drop interface using Oracle VBCS. You can counter the IT backlog due to the fast and increasing demands of mordern business by quickly building an departmental mobile or web applications.

You don't need to install any software development tools-With the Oracle Visual builder Cloud Service or Oracle Intergration Cloud Service you are good to go!. 
VBCS leverages the low code development approach. 

*Steps on creating a simple VBCS mobile application.*

I have been reading alot of late, thus i will create a simple book tracking system. We shall leverage on data from a csv file.

Log in to your [Oracle Cloud Account.](https://cloud.oracle.com/home)

Go to the Visiual Builder Cloud service or Oracle Integration Cloud and select Visual Builder.
Create new application.

![_config.yml]({{ site.baseurl }}/images/images1.JPG)

Your landing page looks like this. 

![_config.yml]({{ site.baseurl }}/images/image3.JPG)

Select Mobile application and give it a name.

We first need to create a Business Object. In my case we shall import data from this [csv file](({{ site.baseurl }}/images/BooksCatalog.xlsv). They data could also be from a service connection on a REST API. 
On the left most menu of the window. Select Business Objects then click on the hamburger menu and select data manager. 

![_config.yml]({{ site.baseurl }}/images/image5.JPG)

Import the BooksCatalog data file. (The download link for the file is above)

Go back to the building interface. 

Drag and drop a ListView from the Components pallet. 

![_config.yml]({{ site.baseurl }}/images/image6.JPG)

Click on Add Data.
Select the Business Object you created (BooksCatalog) 
Follow the wizard to display only BookTitle and author. 
No Queries to define-> click save.
This would be the outcome.

![_config.yml]({{ site.baseurl }}/images/image7.JPG)

Now let's add an action when somebody clicks on the item on the Listview. We want to someone to see more details about the book ie. Description & Published Dates.
Select on the List view. Click on the data Icon. Then click on the "Add Details Page"

![_config.yml]({{ site.baseurl }}/images/image8.JPG)

Select the Business Object on the Wizard.
Drag and drop Booktitle, Description, PublishDate on the "Fields" area.
Click Finish.

You can now test the app by clicking on the Live button. Select a row on the list view.

![_config.yml]({{ site.baseurl }}/images/image9.JPG)

Let's add a book! 

Click back to design view and click on the list view to highlight it. Select "Add a create page"

The same steps like above apply -> select the business objects and select the objects to be inputed. 

The finished screen should look like this-> 

![_config.yml]({{ site.baseurl }}/images/image10.JPG)

Click on the play button to test your application!

![_config.yml]({{ site.baseurl }}/images/image11.JPG)

You can also add more features like edit, delete or connect to your enterprise software etc!

Below is a demo video of the application we just created.

##demo video.

You can download the skeleton application i just created [here]

If you have any questions regarding VBCS feel free to reach out to me. 

I would love to hear your feedback too, comment below, and share if you can, sharing is caring! 

Thank you!

*The views expressed in this blog are my own and do not necessarily reflect the views of Oracle Corporation.*






