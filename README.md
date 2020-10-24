# google-product

Nama  : Farhan Yusuf Akbar  
NIM   : 13519202  

## What is Google BigQuery?

![GoogleBiqQuery](https://user-images.githubusercontent.com/68521556/97081152-a786d100-162a-11eb-872f-414756dd8760.png)


Storing and querying massive datasets can be time consuming and expensive without the right hardware and infrastructure. BigQuery is an enterprise data warehouse that solves this problem by enabling super-fast SQL queries using the processing power of Google's infrastructure. It can easily store exa-byte of data, as well as run frequent queries over petabytes of it. Everything is encrypted, durable, and highly available. And these are some of the features that make BigQuery really unique.  
-It's fully managed and serverless.  
-It handles streaming data to provide real time analytics.  
-It has built in support for machine learning and GIS  
-High speed in-memory BI engine for instant interactive dashboards.  

How is Google Cloud putting all of this together to build our vision of what a data warehouse of the future should look like?  
### Storage and compute  
A data warehouse should handle storage and compute. And by that, the ability to collect all the data we need to have together and the ability to analyze it and combine it at any scale.  
### Serverless  
To pull this off, we really want our data warehouse to be truly serverless. We get to decide on our data and the queries we want to run on it, while BiqQuery take care of running everything else behind the scenes. And what's the magic behind the scenes? BigQuery's architecture that separates storage from compute and a petabyte network connecting both sides.  
### Real-time  
A modern data warehouse should be able to work with real time data.  
### Centralized storage.  
BigQuery can store all of our data and analyze it. But what if we want to read it from other systems? BI tools, Batch and Stream processors, Hadoop, Spark, machine learning platforms, they should allbe able to read data storage BigQuery. BigQuery stores API to enable fast parallel rates without the need of exporting data first.  
### Security  
To make sure Google can put BigQuery into the hands of their most sensitive customers, they have developed features with it, like customer managed encryption keys and access transparency. If anyone managing our cloud data warehouse has to look at our data, we hould know when and why this happened.  
### Data sharing.  
We want to make BigQuery available to anyone that needs to analyze data in our organization. On one hand, Google have a strong permission model. But they also want to make the power of data accessible to those who need it. So with BigQuery, we can save and share queries, as well as data sets. And our analyst can create beautiful reports with Data Studio and third party tools. And to make all of these reports fast and scalable, BI Engine is a new block that acts as a transparent catch in between, an in-memory database that knows when to bring data from the back end, where we only need to decide how much memory we want it to have. And Google is making BigQuery increasingly accessible, even to users that would rather do everything in a spreadsheet.  
### Predictive.  
With infinite storage, we can know what happened in the past. With real time streaming data, we can tell what's happening now. And with machine learning capabilities, we can predict what will happen next. Now BigQuery saved room to create and run machine learning models natively, inside. We can create a model and then use it to predict, within BigQuery and only using a couple SQL commands. To the initial linear and logistic regression models, Google has added K-Means clustering, and matrix factorization, and even the ability to import any TensorFlow model we created outside BigQuery, and even trained TensorFlow models without leaving our favorite data warehouse.  
