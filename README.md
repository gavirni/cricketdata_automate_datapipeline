# cricketdata_automate_datapipeline
<<<<<<< HEAD

This repository contains an automated data pipeline built using Apache Airflow, Google Cloud Functions, Dataflow, and BigQuery to extract, process, and analyze data from an external API.

## Project Overview

In this project, we build a comprehensive data pipeline for processing cricket statistics using Google Cloud services. The pipeline extracts data from the Cricbuzz API, processes it, and stores it in BigQuery for further analysis and visualization using Looker Studio.

## Architecture

![Architecture](https://github.com/vishal-bulbule/cricket-stat-data-engineering-project/blob/master/Architecture.png)

## Data Retrieval with Python and Cricbuzz API
The foundation of our project begins with Python’s prowess in interfacing with APIs. We’ll delve into the methods of fetching cricket statistics from the Cricbuzz API, harnessing the power of Python to gather the required data efficiently.

## Storing Data in Google Cloud Storage (GCS)
Once the data is obtained, our next step involves preserving it securely in the cloud. We’ll explore how to store this data in a CSV format within Google Cloud Storage (GCS), ensuring accessibility and scalability for future processing.

## Creating a Cloud Function Trigger
With our data safely stored, we proceed to set up a Cloud Function that acts as the catalyst for our pipeline. This function triggers upon file upload to the GCS bucket, serving as the initiator for our subsequent data processing steps.

## Execution of the Cloud Function
Within the Cloud Function, intricate code is crafted to precisely trigger a Dataflow job. We’ll meticulously handle triggers and pass the requisite parameters to seamlessly initiate the Dataflow job, ensuring a smooth flow of data processing.

## Dataflow Job for BigQuery
The core of our pipeline lies in the Dataflow job. Triggered by the Cloud Function, this job orchestrates the transfer of data from the CSV file in GCS to BigQuery. We’ll meticulously configure the job settings to ensure optimal performance and accurate data ingestion into BigQuery.

## Looker Dashboard Creation
Finally, we’ll explore the potential of BigQuery as a data source for Looker Studio. Configuring Looker to connect with BigQuery, we’ll create a visually compelling dashboard. This dashboard will serve as the visualization hub, enabling insightful analysis based on the data loaded from our cricket statistics pipeline.

![Looker](https://github.com/vishal-bulbule/cricket-stat-data-engineering-project/blob/master/Looker.png)
=======
This repository contains an automated data pipeline built using Apache Airflow, Google Cloud Functions, Dataflow, and BigQuery to extract, process, and analyze data from an external API.
>>>>>>> 47953f79d5814c9b630c9b037a1ef2905d4afafa
