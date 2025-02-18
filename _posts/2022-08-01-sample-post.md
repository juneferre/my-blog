---

layout: post
title: "Tableau Data Visualizations for Beginners"
author: "June Ferre"
description: "A quick tutorial on 3 basic Tableau Data Visualizations"
image: /assets/images/post1/tableau.jpg

---

### **What is Tableau?** 
Tableau is one of the most common data visualization tools used in a variety of industries, like finance, healthcare, retail, and technology, to help make data-driven decisions. Its is a platform that allows you to create interactive dashboards by taking raw data and transforming it into understandable visualizations with minimal coding–if any. This tutorial is going to cover how to make 3 basic visualizations–a bar chart, line chart, and pie chart–in Tableau, as these are some of the most fundamental ways to present data. 

#### **Downloading Tableau and Basic Navigation**
 This tutorial is assuming you already have Tableau downloaded. If you're completely new to Tableau, I recommend you go watch [this YouTube video](https://www.youtube.com/watch?v=QYnkudCxbmE) on how to download Tableau Desktop and learn the basic navigation within the interface. I also wanted to preface that I'm using a Mac in this tutorial, so if you're using a Windows, steps might be slightly different.

### **Importing Data**  

#### **Choosing the File Format and Selecting your Data**
While in the Home Screen of Tableau, you're going to locate the blue "Connect" sidebar on the left. Under the "To a File" subheading, choose the appropriate option for your data type. 

My data (from [kaggle](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data)),  is in a .csv file, so I'm using the “more” option and navigate to my data file on my computer. Upon finding the data, you select the data file, and click the "open" button. 


<p align="center">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/importingdata.jpg" width="25%" style="display: inline-block; margin-right: 10px;">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/importingdata2.jpg" width="60%" style="display: inline-block;">
</p>




### **Data Visualizations**

After importing the data, you'll be looking at a screen that looks something like the screenshot below. From there, you are going to find the bottom left corner of the screen and select the box that says "Sheet 1". This will take you to the page where we can make data visualizations.  

<p align='center'>
    <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/goingtosheet.jpg" alt="Description" style="width:70%; height:auto;">
</p>




### **Bar Chart**
The first visualization we are going to make is a Bar Chart. Bar charts are most useful when comparing categorical data or ranking items. Making a bar chart in Tableau is pretty fool proof, so lets get into it!


#### **Step 1: Ask a Question**
Once you're on the "Sheet 1" page, look to the "Tables" bar on the left and come up with a question you might have about the categorical data.

If you're following along with the Palmer Penguins dataset, my question is if there is a signifcant difference in flipper lengths between sexes within a penguin species. 



#### **Step 2: Choose Categories then Drag and Drop**
Now you're going to choose the categories you want to compare! I'm choosing three variables: species and sex (belonging to the column variables) and flipper length as our row variable. 

Drag and drop these variables from the "Table" section to the "Rows" and "Columns" boxes

<p align="center">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/columns_rows.jpg" width="30%" style="display: inline-block; margin-right: 10px;">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/withOrange.jpg" width="60%" style="display: inline-block;">
</p>




#### **Step 3: Adjust the Aesthetics** 

#### **Removing an element**
If you have an element you would like to exclude, Tableau's interface makes it quite easy to remove it. 

Click on the bar you'd like removed and click "exclude" as shown below, and bam. It's gone. Below is a side by side of before (left) and after (right). 

<p align="center">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/excludingOrange.jpg" width="45%" style="display: inline-block; margin-right: 10px;">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/afterExcludingOrange.jpg" width="45%" style="display: inline-block;">
</p>




#### **Changing the colors**
Changing the colors on the bar graphs is simple! You're first going to click on the box with colored dots, then press edit colors, select the column you want to change, and choose your color! If that didn't make sense, the image below on the left has some arrows to guide you through the process! The image on the right is the final product. 

<p align="center">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/changingBarcolor.jpg" width="60%" style="display: inline-block; margin-right: 10px;">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/purplebar.jpg" width="30%" style="display: inline-block;">
</p>




Changing the aesthetics of your graphics is a great way to display your creativity as well as stay organized and consistent in your data presentation. There are many more ways to alter and change your graphic! Feel free to explore a few, like the size or label. 


### **Line Graph**
Next, we are going to make a line graph. Line graphs have many uses, some of which include visualizing data trends over time, comparing multiple data series, highlighting rate of change, and detecting patterns and cycles.  

If you want to follow along, we are going to switch from the Penguin data and use [the Superstore Sales dataset](https://public.tableau.com/app/learn/sample-data?_gl=1*1628m6b*_ga*MTMzNTg4MDQ1My4xNzM4Njk5MzA5*_ga_8YLN0SNXVS*MTczODY5OTMwOC4xLjEuMTczODY5OTMwOS4wLjAuMA..) from Tableau's sample data to look at a Superstore's sales trends.

Luckily making bar charts and line charts are essentially the same processs, so you're just going to import your data, and then repeat steps 1-3 of the bar chart instructions. Make sure to use variables that deal with time and to select the line chart option. Down below is an example of what it might look like for you!

<p align='center'>
    <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/linechart.jpg" alt="Description" style="width:70%; height:auto;">
</p>




### **Pie Chart**
Pie Charts are used to show part-to-whole relationships, emphasizing proportions. These could be great for showing population demographics, budget allocation, sales distribution, survey results, and more! 

Pie charts are slightly trickier than the bar chart and line graph, so I'm going to walk you through it step by step! If you're wanting to follow along with the same data, I'm going to be using the [Superstore Sales dataset](https://public.tableau.com/app/learn/sample-data?_gl=1*1628m6b*_ga*MTMzNTg4MDQ1My4xNzM4Njk5MzA5*_ga_8YLN0SNXVS*MTczODY5OTMwOC4xLjEuMTczODY5OTMwOS4wLjAuMA..) from Tableau's sample data again. 



### **Step 1: Grab the dimmension you're going to use to separate the pie chart with**
You want to grab the element of "dimmension" you want the pie chart to be separated by, and drag and drop it into the "color" boxI'm going to grab the "Segment" and drag and drop it into the "Color" box. You should end up with something like the screenshot on the right. 

<p align="center">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/segment.jpg" width="45%" style="display: inline-block; margin-right: 10px;">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/aftersegment.jpg" width="45%" style="display: inline-block;">
</p>




### **Step 2: Specify that you want a Pie Chart**

Next, you're going to specifiy that you'll be using a pie chart. To do this you're going to select the arrow next to the "Automatic" drop down menu in the Marks box. Navigate to "Pie" and select it. You should end up with a pie chart separated into three equal parts (as shown on the right).

<p align="center">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/makepie.jpg" width="40%" style="display: inline-block; margin-right: 10px;">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/pie.jpg" width="50%" style="display: inline-block;">
</p>




#### **Optional: Changing the Segment Separator**

I want to make my pie chart segments a little clearer, so I'm going to change my separating line to white. This is a matter of preference, so not necessary. Follow the arrows below to change the separators!

<p align='center'>
    <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/separators.jpg" alt="Description" style="width:50%; height:auto;">
</p>




### **Step 3: Select Metric you want to drive your Pie Chart**

I want to separate my pie chart by the Sales categories, so I'm going to select the "Sales" and drag and drop it onto "Detail". This is going to add Sales to the Angle, which will segment the pie chart proportional to the sum of sales for each category. 

<p align='center'>
    <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/salesDet.jpg" alt="Description" style="width:50%; height:auto;">
</p>




### **Step 4: Change the Sales to Percentage of Total**

Now we are going to convert the "Sales" metric to display as a percentage of total instead of raw values. This makes the pie chart more meaningful, as each segment will now represent its proportion of total sales rather than absolute numbers. 

To do this, you're going to click the arrow on the "SUM(Sales)". On that drop down menu, you'll hover over the "Quick Table Calculation", then select "Percent of Total". 

<p align='center'>
    <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/changetoPOT.jpg" alt="Description" style="width:40%; height:auto;">
</p>




It will look like no changes have been made to the pie chart, but don't worry! We're going to fix that in the next step. 

### **Step 5: Change the angle**

To change the angle proportions, you're going to drag the "SUM(angle)" element to the "Angle" box. After doing that, you're pie chart should have changed the proportions of the segments, looking something like the screenshot on the right.

<p align="center">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/sumtoangle.jpg" width="45%" style="display: inline-block; margin-right: 10px;">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/afterangle.jpg" width="45%" style="display: inline-block;">
</p>




### **Step 6: Making labels**

A pie chart without labels or a legend, would be pretty meaningless, so we're going to add labels. We'll do this by dragging the metric (Sales) to the label box to make a metric label. You're labels will look like the screenshot on the right. 

<p align="center">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/sumtolabel.jpg" width="45%" style="display: inline-block; margin-right: 10px;">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/label.jpg" width="45%" style="display: inline-block;">
</p>




#### **Changing Views**

We are now going to change the view of the pie chart to make it look bigger. To do that we are going to navigate to the "Standard" box in the top menu bar, select the arrow for the drop down menu, and select "Entire View". You'll end up with a magnified pie chart in the middle of your screen (as shown on the right).

<p align="center">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/standard.jpg" width="30%" style="display: inline-block; margin-right: 10px;">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/bigview.jpg" width="60%" style="display: inline-block;">
</p>




### **Adding More Labels**
The numbers aren't very interpretable just on their own, so we are going to add the dimmension label too, to enhance clarity. 

To do that we are going to drag the "Segment" element to the Label box. You're finished product should something like the screenshot on the right! You know how to change the colors and other aesthetics, so feel free to play around with those things too. 

<p align="center">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/segmentlabel.jpg" width="40%" style="display: inline-block; margin-right: 10px;">
  <img src="{{site.url}}/{{site.baseurl}}/assets/images/post1/finished.jpg" width="50%" style="display: inline-block;">
</p>




## **That's It! You did it!**
You now know the basics of simple Tableau data visualizations! As you can see, Tableau is a great, user-friendly way to make raw data meaningful. These charts are just the beginning of all the ways you can make your data meaningful. I hope you found this basic tutorial helpful! I challenge you to go find another dataset and try making these graphics with your data. Thanks for reading! 

