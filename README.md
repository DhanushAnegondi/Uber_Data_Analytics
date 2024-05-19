# Uber Data Analysis Project

## Overview

This project demonstrates a complete ETL (Extract, Transform, Load) pipeline using Mage AI, an open-source tool. The project involves loading data from Google Cloud Storage, transforming the data, and exporting it to Google BigQuery. The final dataset is then used to create a dashboard in Looker Studio.

## Architecture

![Project Architecture](path/to/your/architecture/image.png)

## GCP Services Used

- **Google Cloud Storage**: Used to store raw data. Data is uploaded from the local machine to the GCP bucket.
- **Google Compute Engine**: A VM instance is used to install necessary libraries and run the Mage AI pipeline.
- **Google BigQuery**: Used to store the transformed data for analysis.
- **Looker Studio**: A web-based tool for creating interactive dashboards and reports from BigQuery data.

## Project Steps

### 1. Setting Up the Environment

**Install Python and pip:**
```bash
sudo apt-get update
sudo apt-get install python3-distutils
sudo apt-get install python3-apt
sudo apt-get install wget
wget https://bootstrap.pypa.io/get-pip.py
sudo python3 get-pip.py
```

**Install Mage AI:**
```bash
sudo pip3 install mage-ai
```

**Install Pandas:**
```bash
sudo pip3 install pandas
```

**Install Google Cloud Libraries:**
```bash
sudo pip3 install google-cloud
sudo pip3 install google-cloud-bigquery
```

### 2. Uploading Data to Google Cloud Storage

Upload your local data files to the Google Cloud Storage bucket and make them publicly accessible.

### 3. Running Mage AI

**Launch Mage AI:**
```bash
mage start
```

### 4. Loading Data from GCP Bucket

Configure the Mage AI pipeline to load data from the publicly accessible URL of the GCP bucket.

### 5. Transforming Data

Use Mage AI's transformation capabilities to clean and prepare the data for analysis.

### 6. Exporting Data to BigQuery

Export the transformed data to a BigQuery dataset created for this project.

### 7. Creating Dashboards in Looker Studio

Use the data in BigQuery to create interactive dashboards in Looker Studio. You can view the dashboard [here](https://lookerstudio.google.com/s/nrmoVL-XXpg).


## Conclusion

This project showcases how to effectively use Mage AI for data engineering tasks, integrating various GCP services to build a robust data pipeline. The final output provides valuable insights through interactive dashboards in Looker Studio.