# Introduction

Thanks for applying at the Rabobank! As part of the application process for the job of Data Scientist at Rabobank an assessment is made of your technical and quantitative skills. In this assessment you are asked to develop and present a case study. This document will further elaborate on the details of this case. Please complete the assignment in Python. We use PySpark in our day-to-day work, but feel free to use any Python libraries you prefer. If you do not have PySpark installed, it’s better to use another library.
<br/><br/>

# Case description

As a guardian of the financial system, Rabobank needs to know their customers and what behaviour to expect from them. Hence, every day we are working on improving these insights in various projects, such as Transaction Monitoring or by uncovering the source of funds for businesses. Today, you will be working on gaining insights into our customers and their transaction behaviour. What is expected from them and who is acting outside of these expectations?
<br/><br/>
The business wants to understand which customers are closely related to each other in their transactional patterns so that they can create a unified approach in dealing with these customers. In addition, any customers that are acting in an anomalous way will pique their interest, as it might be a potential indicator for suspicious or undesired payments. So they want to you provide them with the necessary insights based on patterns you have found in the transaction data.
<br/><br/>
Our request to you, please come up with an approach on how to identify clusters of customers, find the anomalies and give the business insights they can work with. Please be aware that no customer is by definition suspicious; we have human safeguards in place that will evaluate the outcome of any model. However, that does not mean we should not focus on explainability, this is still a major focus point in any model created.
<br/><br/>

# Data

You will have four datasets at your disposal. These contain transactions done on different payment accounts. In addition, there is customer information available to you. To link these two together, there is a mapping between accounts and customers. On top of that, you will find a reference table with the descriptions of the transaction types ('tx_tp') in the transactions table.
<br/><br/>
During the case discussion, please walk us through your thought process and show the insights you gained. Focus on how you can get your message across to a business audience as well. The end goal is an unsupervised model, but our focus will be on how you get there, not on the actual workings of the model. Furthermore, keep in mind that to get the most value out of such a project, we will need to put it live in production. We are curious to hear your thoughts on this when discussing how to create business value with your created model.
<br/><br/>
When writing your code, focus on readability and a clear structure of your logic. You could do so by separating logic into multiple functions. As they say, code is read more often than written. Plus, it helps us a lot in understanding your reasoning.
<br/><br/>

# Schedule

In the case interview, we will discuss the case for 20 minutes, after which we have 10 minutes to go through the business implications.
<br/><br/>
