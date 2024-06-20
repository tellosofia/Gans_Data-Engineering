# Case Study: Optimizing Gans' Data Pipeline

## Background
Gans is a startup developing an e-scooter-sharing system aspiring to operate in the world's most populous cities. Gans aims to optimize scooter availability by anticipating movement patterns, a task requiring sophisticated data collection and processing.

## Objectives
The project aims to create an automated data pipeline to predict e-scooter movements. Key questions include:
- How can data be collected effectively from external sources?
- What database structure is needed to store this data?
- How can the pipeline be automated and scaled using cloud services?

## Project Overview and Deliverables
Creating an automated data pipeline involves two major phases:

### Local Pipeline – Phase 1
1. **Scrape Data from the Web:** Using Python's BeautifulSoup to download and extract HTML content.
2. **Collect Data with APIs:** Utilize Python’s requests library to authenticate and assemble API requests.
3. **Create a Database Model:** Define the logical structure of the database.
4. **Store Data Locally:** Set up a MySQL database and store the collected data.

### Cloud Pipeline – Phase 2
1. **Set up a Cloud Database:** Use AWS RDS to create a MySQL database in the cloud.
2. **Move Scripts to Lambda:** Transition data collection scripts to AWS Lambda functions.
3. **Automate the Pipeline:** Use AWS CloudWatch Events / EventBridge to schedule and automate script execution.

## Tools and Technologies
- **Programming Languages:** Python
- **Web Scraping:** BeautifulSoup
- **API Interaction:** requests library
- **Database Management:** MySQL, AWS RDS
- **Cloud Services:** AWS Lambda, AWS CloudWatch

## Expected Outcomes
The project will result in an efficient data pipeline that collects and stores real-time data to predict e-scooter movements. This will help Gans improve scooter availability and operational efficiency. Key deliverables include a fully operational data pipeline and a Medium article detailing a subject covered during the project.


