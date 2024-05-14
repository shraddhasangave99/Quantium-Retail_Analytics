# Quantium-Retail_Analytics
  As the part of the Quantium Data Analytics Virtual Internship offered by Forage, I have worked on this data analysis project. It contains results of the completed tasks for the [Quantium Virtual Internship](https://www.theforage.com/simulations/quantium/data-analytics-rqkb), designed to replicate life in the Retail Analytics and Strategy team at Quantium, using Python.

![Image](https://github.com/shraddhasangave99/Quantium-Retail_Analytics/assets/153710836/8ea552bb-3482-44a2-83d7-f1818fb29ff1)

## Introduction
  Quantium has maintained a data collaboration with a major retail chain for several years, wherein the retailer furnishes transactional and customer data. As an analyst within Quantium's analytics team, the role involves delivering invaluable data analytics and insights to aid strategic decision-making.

  Retailers frequently adjust their store layouts, product assortments, pricing strategies, and promotional activities. These adaptations are aimed at addressing evolving customer preferences, staying competitive in the market, or seizing new opportunities. The Quantium analytics team plays a crucial role in assessing and analyzing the impact of these changes and advising on their effectiveness.

### Things learnt from this program
🔸Data wrangling
🔸Data visualization
🔸Statistics

🔸Programming skills
🔸Commercial thinking
🔸Critical thinking

## Task 1

### Data preparation and customer analytics
Conduct analysis on your client's transaction dataset and identify customer purchasing behaviours to generate insights and provide commercial recommendations.

Here is the background information of the task:

You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region.

The insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.

![Task 1 Img](https://github.com/shraddhasangave99/Quantium-Retail_Analytics/assets/153710836/dd4de9ea-865e-40c5-9715-26535c6f2d00)

Here is the task:

We need to present a strategic recommendation to Julia that is supported by data which she can then use for the upcoming category review however to do so we need to analyse the data to understand the current purchasing trends and behaviours. The client is particularly interested in customer segments and their chip purchasing behaviour. Consider what metrics would help describe the customers’ purchasing behaviour.

To get started, download the resource csv data files below and begin performing high level data checks such as:

 ▪️ Creating and interpreting high level summaries of the data
 
 ▪️ Finding outliers and removing these (if applicable)
 
 ▪️ Checking data formats and correcting (if applicable)

You will also want to derive extra features such as pack size and brand name from the data and define metrics of interest to enable you to draw insights on who spends on chips and what drives spends for each customer segment. Remember our end goal is to form a strategy based on the findings to provide a clear recommendation to Julia the Category Manager so make sure your insights can have a commercial application.

LIFESTAGE: Customer attribute that identifies whether a customer has a family or not and what point in life they are at e.g. are their children in pre-school/primary/secondary school.

PREMIUM_CUSTOMER: Customer segmentation used to differentiate shoppers by the price point of products they buy and the types of products they buy. It is used to identify whether customers may spend more for quality or brand or whether they will purchase the cheapest options.

## Task 2

### Experimentation and uplift testing

Extend your analysis from Task 1 to help you identify benchmark stores that allow you to test the impact of the trial store layouts on customer sales.

Here is the background information of the task:

You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, has asked us to test the impact of the new trial layouts with a data driven recommendation to whether or not the trial layout should be rolled out to all their stores.

![Task 2 img](https://github.com/shraddhasangave99/Quantium-Retail_Analytics/assets/153710836/915007ca-2c43-44eb-a11e-8789f3c581f3)

Here is the task:

Julia has asked us to evaluate the performance of a store trial which was performed in stores 77, 86 and 88.

To get started use the QVI_data dataset below or your output from task 1 and consider the monthly sales experience of each store.

This can be broken down by:

 ▪️ total sales revenue
 
 ▪️ total number of customers
 
 ▪️ average number of transactions per customer

Create a measure to compare different control stores to each of the trial stores to do this write a function to reduce having to re-do the analysis for each trial store. Consider using Pearson correlations or a metric such as a magnitude distance e.g. 1- (Observed distance – minimum distance)/(Maximum distance – minimum distance) as a measure.

Once you have selected your control stores, compare each trial and control pair during the trial period. You want to test if total sales are significantly different in the trial period and if so, check if the driver of change is more purchasing customers or more purchases per customers etc.

## Task 3

### Analytics and commercial application
Use your analytics and insights from Task 1 and 2 to prepare a report for your client, the Category Manager.

Here is the background information of the task:

Task 3 is targeted specifically at building your ability to recognise commercial, actionable insights from your analysis and displaying it in a clear and concise way for your client, with minimal jargon. At Quantium, our analyst graduates sometimes work as what we like to call "hybrids" (a mix of analyst and consultant duties) so developing your presentation skills early is a huge win!

As both technical tasks 1 and 2 were open ended in terms of insights, this model answer will focus on the layout and the order of your inclusions, including where to include graphs, taglines, written insights and recommendations.

As part of Quantium’s retail analytics team, you have been conducting a range of analysis on transaction and purchase behaviour data to provide key recommendations to your client, the Category Manager of chips, who is putting together their strategic plan.

![Task3 img](https://github.com/shraddhasangave99/Quantium-Retail_Analytics/assets/153710836/baa5d6ec-486b-49ef-94ca-85293b1e5bf1)

Here is the task:

With our project coming to an end its time for us to send a report to Julia, based on our analytics from the previous tasks. We want to provide her with insights and recommendations that she can use when developing the strategic plan for the next half year.

As best practice at Quantium, we like to use the "Pyramid Principles" framework when putting together a report for our clients. If you are not already familiar with this framework you can find quick introductions on by searching form them on the internet.

For this report, we need to include data visualisations, key callouts, insights as well as recommendations and/or next steps.

 key considerations for a presentation we should keep in mind:

🔸Data literacy level of your audience
🔸Table of contents / agenda
🔸Problem statement / purpose
🔸Overview and context
🔸Content balance
🔸Layout and content display
🔸Summary / next steps

