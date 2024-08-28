# Cassandra Data Modeling Project

- This repository contains a data engineering project focused on data modeling, querying, and management using Apache Cassandra. 
- The goal of this project is to efficiently store, retrieve, and manage large datasets, leveraging Cassandras distributed architecture. 

## Project Overview

- In the era of big data, managing and querying large-scale datasets efficiently is crucial. Apache Cassandra, with its distributed database model, offers robust support for such tasks. 
- This project demonstrates the process of setting up data models in Cassandra, executing queries, and managing the data lifecycle.

## Project Structure

1. **Data Modeling**:
   - Creation of tables to store information, such as session and song details, following best practices for efficient data retrieval.

2. **Data Insertion**:
   - Populating the tables with data related to user sessions, songs played, and other relevant information.

3. **Data Querying**:
   - Executing queries to extract insights, such as the most played songs during a session or user-specific activity details.

4. **Validation**:
   - Ensuring that the queries return accurate results, matching the expected output.

5. **Cleanup**:
   - Dropping tables and closing sessions to ensure resources are freed after the data operations are complete.

'
## How to Run

To run this project, clone the repository and ensure you have Apache Cassandra and the required Python dependencies installed. The project is implemented in a Jupyter notebook, so you will need Jupyter installed on your machine.

### Dependencies

	•	Python 3.x
	•	Apache Cassandra - (For Apache Cassandra i have installed it on my device, if there is any issue related to apache cassendra you use docker method, refer the file in repository named "Docker-compose.yml".)  
	•	Jupyter Notebook or jupyter Lab
	•	Pandas
	•	Cassandra Driver for Python
