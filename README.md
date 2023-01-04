# NLP Assignment - Ticket Recommendation System
The notebook explores on creation of a ticket recommendation system for client's complains data.

Problem statement:
-Prepare solution to build ticketing system there by using json file as your primary datasource (Text corpus with other metadata in it). 
Step 1: Group data into five categories namely Banking services, loans, Fraudalent reporting, Card, others.
Step 2: From step 1 create labeled dataset and utilize it to train supervised model like logistic regression, decision tree or random forest.


Above excercise should follow these steps -
Load Data
Text Preprocessing
EDA
Feature Extraction
Topic Modelling (Unsupervised)
Model building using Supervised learning
Model Training and evaluation
Inference

Solutioning:
We need to build a model that is able to classify Customer Complaints based on the products/services. By doing so you can segregate these tickets into their relevant categories.

As data is not labeled, we apply NMF to analyse patterns and classify the tickets into the following 5 clusters based on the products/services.

- **Credit/Prepaid Card**
- **Bank Account Services**
- **Theft/Dispute Reporting**
- **Mortgages/Loans**
- **Others**

Approach:
## Steps: 
* 1. Import libraries 
* 2. Perform EDA  
* 3. Pre-process data 
* 4. Topic modelling 
* 5. Identify the n best topics 
* 6. Map complaints to topics 
* 7. Create labelled dataset for supervised learning 
* 8. Train-test split of data 9.Train model on various algorithm 
* 10. Select the best model 
* 11. Classify any new customer complaint ticket with the trained model
