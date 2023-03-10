# Automation-in-Ticketing-System
NLP based project

When an issue or support ticket appears in your help desk, it needs to be processed and assigned a tag (or category) so that it’s routed to the correct team 
member. This will either be manual, which involves reading the ticket and manually assigning a tag, or automatic


Objective was to build a model that is able to classify customer complaints based on the products/services, to segregate these tickets into their relevant 
categories and, therefore, help in the quick resolution of the issue.



After loading the data, text preparation using tokenization, lemmatization, etc, exploratory data analysis (EDA), and feature extraction were performed.

Complaints were divided into five clusters depending on their products/services using topic modelling.

After translating the word vector to a tf-idf model, classification was performed using supervised learning like logistic regression, decision tree and random 
forest.


You must create a model that can categorise consumer complaints depending on the products/services. By doing so, you can categorise these tickets and so aid in the speedy resolution of the issue.

Topic modelling will be performed on the.json data provided by the company. Because this data is unlabeled, you must use NMF to analyse patterns and classify tickets into the five clusters depending on their products/services:


Prepaid card / credit card

Services for bank accounts

Reporting Theft/Disputes

Mortgages/loans

Others

You will be able to map each ticket to its respective department/category using topic modelling. This data can then be used to train any supervised model, including logistic regression, decision trees, and random forests. You can use this trained model to assign any new customer complaint support ticket to the appropriate department.
