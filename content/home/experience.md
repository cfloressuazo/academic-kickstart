+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Engineering Manager"
  company = "YGroup Companies"
  company_url = "https://www.ygroupcompanies.com/"
  location = "Amsterdam, NL"
  date_start = "2020-03-01"
  date_end = ""
  description = """
  
  I managed an engineering team building an enterprise data platform that serves as a central point for BI and analytics for Carlsberg.
  
  The platform was setup using Microsoft Azure cloud services and Databricks.
  
  The approach taken was of a self-service platform architecture, where data from business domains get loaded into the Data Lake via Integration Pipelines and then transformed and loaded into a semantic layer in a Data Warehouse via ETL processes written on PySpark. 
  
  The face of our platform was the Power BI implemented for the business.
  
  The team consisted of one BI Architect, one BI Engineer, one Scrum Master, two Data Engineers, and myself. (We worked remotely most of the time because of Corona...)
  
  Responsibilities include:
  
  * Project Management
  * Product Roadmap and Goal Settings
  * Communication with stakeholders
  * Direction and Technical leadership
  """

[[experience]]
  title = "Senior Data Engineer"
  company = "YGroup Companies"
  company_url = "https://www.ygroupcompanies.com/"
  location = "Amsterdam, NL"
  date_start = "2018-07-01"
  date_end = ""
  description = """
  
  As a Senior Data Engineer at a consultancy company I was providing guidance in the implementation of Data Platforms for enterprises, developing data products and assuring that the development of these followed the best practices in the industry. 
  I helped three big clients of YGroup during this time.
  
  **Carlsberg Breweries A/S**
  
  I was responsible for the engineering and the deployment of machine learning models in production for two main data products: Demand Forecast for Supply Chain and Customer Churn.
  
  The tools were built on python and R for POC purposes but then they needed to be re-developed in PySpark due to the size of data and because of the production ecosystem. 
  
  I worked on guiding and developing different modules of the tools, including the feature engineering, data loader functions and inference functions. The tools went live and are currently running as a critical part of the Supply Chain team and the Customer Service Team @ Carlsberg.
  
  **SHV Holdings N.V.**
  
  I was responsible of building the holdings' data platform. The data platform was built using MS Azure, with a data lake approach using Data Lake Storage Gen2, a Data Warehouse (Azure Synapse), an integration service (Azure Data Factory) and an ETL tool for data processing. 
  
  The ETL tool was Airflow running in a Docker container in Azure. 
  
  I developed a set of data pipelines that had the objective of bringing data to the analytics layer for P&L Reporting, Claims and Corporate Expenses.
  
  
  **Stern NL**
  
  I was responsible of setting up the MS Azure services for data scientist to consume data and produce analytics relevant for the business. I was then making this data available to the business by loading it into a PostgreSQL data warehouse deployed on Azure. I was also guiding data scientist on best approaches to run on a schedule R scripts to produce this data.
  
  Responsibilties include:

  * Design and implementation of data platforms
  * Machine Learning workflows in production
  * Technical Development of data products
  * Integration of Data Sources
  * ETL Development
  """

[[experience]]
  title = "Team Lead & Data Scientist"
  company = "Intelligens - Conversica"
  company_url = "https://www.conversica.com/"
  location = "Santiago, Chile"
  date_start = "2016-06-01"
  date_end = "2018-07-01"
  description = """
  
  I lead the team developing a natural language processing engine in the company for conversational Artificial Intelligence.
  
  Tech Accomplishment:
  - Quick machine learning deployment pipeline to production for NLP and operational tasks
  - Over 95% Accuracy of models for similar tasks in production for the time period of 2 years
  - Automated more than 70% of operational/product related tasks using Machine Learning

  Responsibilities include:
  * Development a natural approach to accomplish Human-Like Conversational AI.
  * Design the feature roadmap for NLP and Natural Language Understanding into the system.
  * Build Artificial Intelligence customizable process based on user's interaction.
  * Designed, built and managed automated self-learning pipeline.
  * Train and Deploy Machine Learning and Deep Learning Models in production.
  """

[[experience]]
  title = "Data Engineer"
  company = "Equifax"
  company_url = "https://www.equifax.com/"
  location = "Santiago, Chile"
  date_start = "2015-03-01"
  date_end = "2016-07-01"
  description = """
  
  I developed ETL pipelines to bring operational transactions into a data warehouse. 
  I helped on the design of the STAR schema. 
  I also translated business requirements into data table or views.
  I POC'ed a new ETL tool called Pentaho for the team which was later adopted.
  
  """

+++
