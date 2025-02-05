---

layout: post
title: "Tableau Data Visualizations for Beginners"
author: "June Ferre"
description: "A quick tutorial on 3 basic Tableau Data Visualizations"
image: /assets/images/post1/tableau.jpg

---

### **What is Tableau?** 
Tableau is one of the most common data visualization tools used in a variety of industries, like finance, healthcare, retail, and technology, to help make data-driven decisions. Its is a platform that allows you to create interactive dashboards by taking raw data and transforming it into understandable visualizations with minimal coding–if any. This tutorial is going to cover how to make 3 basic visualizations–a bar chart, line chart, and scatter plot–in Tableau. 

### **Downloading Tableau and Basic Navigation**
 This tutorial is assuming you already have Tableau downloaded. If you're completely new to Tableau, I recommend you go watch [this YouTube video](https://www.youtube.com/watch?v=QYnkudCxbmE) on how to download Tableau Desktop and learn the basic navigation within Tableau. 

### **Importing Data** 
Depending on your file type, you import your data by clicking on an option under the “To a File” subheading in the blue “Connect” sidebar on the left of the homescreen.  

#### **Step 1: Choosing the File Format**
Look on the blue panel on the left of the screen and select the file format under the "To a File" subheading. 

My data is in a .csv file so I am using the “more” option and selecting my data from a file on my computer. I got my Palmer Penguin data from [kaggle](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data).

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/importingdata.jpg)




#### **Step 2: Selecting your Data**
Navigate to your file, select, and click the "open" button.

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/importingdata2.jpg)

### **Data Visualizations**
After importing the data, you'll be looking at a screen that looks something like the screenshot below. From there, you are going to find the bottom left corner of the screen and select the box that says "Sheet 1". 

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/goingtosheet.jpg)


### **Bar Chart**
The first visualization we are going to make is a Bar Chart. Bar charts are most useful when comparing categorical data or ranking items. Making a bar chart in Tableau is pretty fool proof!


#### **Step 1: Ask a Question**
Once you're on the "Sheet 1" page, look to the "Tables" bar on the left and come up with a question you might have about the categorical data.

If you're following along with the Palmer Penguins dataset, my question is if there is a signifcant difference in flipper lengths between sexes within a penguin species. 



#### **Step 2: Choose Categories then Drag and Drop**
Choose the categories you want to compare. 

I'm choosing three variables: species and sex (belonging to the column variables) and flipper length as our row variable. 

Drag and drop these variables from the "Table" section to the "Rows" and "Columns" boxes

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/columns_rows.jpg)

The picture below is what your bar chart might look like.

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/withOrange.jpg)

#### **Step 3: Adjust the Aesthetics** 

#### **Removing an element**
If you have an element you would like to exclude, Tableau's interface makes it quite easy to remove it. 

Click on the bar you'd like removed and click "exclude" as shown below

The picture below is what your bar chart might look like.

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/excludingOrange.jpg)

After:

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/afterExcludingOrange.jpg)

#### **Changing the colors**
To change the bar colors, you click on the "Color" box in the "Marks" box.

Follow the arrows to walk you through how to change the colors. 

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/changingBarcolor.jpg)

AFTER: 

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/purplebar.jpg)

There are many more ways to alter and change your graphic! Feel free to explore a few, like the size or label. 

#### **Saving Your Work**
![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/savingbar.jpg)

### **Line Graph**
Line graphs are most appropriate for visualizing data trends overtime. 

For this graph, we are going to use [the Superstore Sales dataset](https://public.tableau.com/app/learn/sample-data?_gl=1*1628m6b*_ga*MTMzNTg4MDQ1My4xNzM4Njk5MzA5*_ga_8YLN0SNXVS*MTczODY5OTMwOC4xLjEuMTczODY5OTMwOS4wLjAuMA..) from Tableau's sample data.

Luckily making bar charts and line charts are essentially the same processs, so you just have to repeat the steps from the bar chart instructions. Here are some pictures down below of what it might look like for you!

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/sheet1forline.jpg)

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/linechart.jpg)

### **Pie Chart**
Pie Charts are made slightly differently than line graphs and bar charts and are used to show part-to-whole relationships, emphasizing proportions. 

For this pie chart I'm going to be using the [Superstore Sales dataset](https://public.tableau.com/app/learn/sample-data?_gl=1*1628m6b*_ga*MTMzNTg4MDQ1My4xNzM4Njk5MzA5*_ga_8YLN0SNXVS*MTczODY5OTMwOC4xLjEuMTczODY5OTMwOS4wLjAuMA..) from Tableau's sample data again. 

### **Step 1: Grab the dimmension you're going to use to separate the pie chart with**
I'm going to grab the "Segment" and drag and drop it into the "Color" box. 

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/segment.jpg)

AFTER:

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/aftersegment.jpg)

### **Step 2: Specify that you want a Pie Chart**

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/makepie.jpg)

AFTER

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/pie.jpg)

### **Step 3: Select Metric you want to drive you Pie Chart**

I'm going to choose "Sales" and drag and drop it onto "Detail".

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/salesDet.jpg)


### **Step 4: Change the Sales to Percentage of Total**

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/changetoPOT.jpg)

### **Step 5: Change the angle**

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/sumtoangle.jpg)

### **Step 5: Make labels**
Move the metric to the label box to make a metric label. In my case, I'm using Sales.

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/sumtolabel.jpg)

AFTER

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/label.jpg)

#### **Changing Views**

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/bigview.jpg)

### **Adding More Labels**
You can add the dimmension label too!

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/segmentlabel.jpg)

After:

![Figure]({{site.url}}/{{site.baseurl}}/assets/images/post1/segmentlabelafter.jpg)

### **Finsished Product**
This is a very basic pie chart, but can get the job done if needs be!

## **That's All**
I hope you found this basic tutorial helpful, I challenge you to go find another dataset and try making these graphics with your data! 