---

layout: post
title: "Tableau Data Visualizations for Beginners"
author: "June Ferre"
description: "A quick tutorial on 3 basic Tableau Data Visualizations"
image: image: /assets/images/post1/tableau.jpg

---

### **What is Tableau?** 
Tableau is one of the most common data visualization tools used in a variety of industries, like finance, healthcare, retail, and technology, to help make data-driven decisions. Its is a platform that allows you to create interactive dashboards by taking raw data and transforming it into understandable visualizations with minimal coding–if any. This tutorial is going to cover how to make 3 basic visualizations–a bar chart, line chart, and scatter plot–in Tableau. 

### **Downloading Tableau and Basic Navigation**
 This tutorial is assuming you already have Tableau downloaded. If you're completely new to Tableau, I recommend you go watch [this YouTube video](https://www.youtube.com/watch?v=QYnkudCxbmE) on how to download Tableau Desktop and learn the basic navigation within Tableau. 

### **Importing Data** 
Depending on your file type, you import your data by clicking on an option under the “To a File” subheading in the blue “Connect” sidebar on the left of the homescreen. My data is in a .csv file so I am using the “more” option and selecting my data from a file on my computer. I got my Palmer Penguin data from [kaggle](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data). 

#### **Step 1: Choosing the File Format**
Look on the blue panel on the left of the screen and select the file format under the "To a File" subheading. 

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/importingdata.jpg)


#### **Step 2: Selecting your Data**
Navigate to your file, select, and click the "open" button.

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/importingdata2.jpg)

### **Data Visualizations**
After importing the data, you'll be looking at a screen that looks something like the screenshot below. From there, you are going to find the bottom left corner of the screen and select the box that says "Sheet 1". 

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/goingtosheet.jpg)

#### **Bar Chart**
The first visualization we are going to make is a Bar Chart. Bar charts are most useful when comparing categorical data or ranking items. Making a bar chart in Tableau is pretty fool proof!


#### **Step 1: Ask a Question**
Once you're on the "Sheet 1" page, look to the "Tables" bar on the left and come up with a question you might have about the categorical data.

If you're following along with the Palmer Penguins dataset, my question is if there is a signifcant difference in flipper lengths between sexes within a penguin species. 



#### **Step 2: Choose Categories then Drag and Drop**
Choose the categories you want to compare. 

I'm choosing three variables: species and sex (belonging to the column variables) and flipper length as our row variable. 

Drag and drop these variables from the "Table" section to the "Rows" and "Columns" boxes

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/columns_rows.jpg)

#### **Step 3: Drag and drop** 
Next 
