---
layout: page
title: "Phase 1- Data Skills"
permalink: /phase1/data-skills
tags: 
  - data-skills
  - data
  - data warehousing
  - data modelling
  - SQL
author:
  name: Mani Nekkalapudi
  github: maninekkalapudi
---

### What are data skills?

Data in and of itself is not valuable or readily consumable. The goal is to make sense of the data and extract meaningful information from it.

Data professionals like data engineers or a data analyst will try to make sense of the data within a business context by applying certain logic to get information from the data.

For example:

- A BI developer will understand the business requirements and generate the reports for business users

- A data scientist will understand the business requirements and develop the models to predict the user behaviours.

Having the domain knowledge of the data combined with technical skills to extract the information are called as data skills.

### Domain Knowledge

It is something that is aquired gradually over the time working in a broader field. It holds all the details of core knowledge of business processes, operations, regulatory compliances and etc., in an organization.

Suppose, you are woking with a company specializes in pharmaceutical domain. Knowing how the domain operates on a boarder level is invaluable in understanding the data itself. Again, this knowledge is completely different from, say, an ecommerce domain.

### Technical Knowledge

Technical knowledge of different systems like databases, BI tools, data processes and others required to function in the relevant role.

For data engineers, knowledge on the data sources like a database, APIs, file servers and the nature of the data itself is pretty important.

SQL is one skill that is common across all the data roles which is used to perform various operations on mostly tabular/relational data.

We also need to understand concepts like Data warehousing and Data Modelling. Lets dive deep in the next section.

### Understanding the Data Skills for Data Engineers

Data engineering team(s) acts as data and knowledge brokers within a company. The data from various operational system within the business will be captured into analytical systems like a data warehouse. Later it will be processed and served to different stakeholders.

Below diagram represents a typical data engineering pipeline with all the activities carried out by the DE team. Lets understand this in the context of skills.

| ![Structured Data](../assets/img/../../../assets/img/data-skills.md/typicaldatapipeline.png) |
|:--:|
| *[A Typical Data Pipeline]*|

**Sources**:

- Sources are typically the operational systems like a database, an API, a CRM system, or a fileserver

- These will record the current state of the business. Ex: Order status in orders table. It will have only the latest order status for the orders

- Operational systems, like a database, are designed to serve millions of customers at once and to update individual records frequently

- knowledge on how the data is caputured in these systems, type of the data, frequency of updates and capturing all those updates into a data warehouse is the primary requirement for the data engineering team

- A data ingestion framework that includes capturing and storing the data for each type of data source will be created. Programming languages like Python or Scala can be used for this task.

**Raw, Staging and Serving**:

- Once the data is ingested, we will convert the raw data into a format specified by the business. This data will be promoted to staging.

- Data in the raw layer can be in different formats like structured, semi-structured and unstructured.
