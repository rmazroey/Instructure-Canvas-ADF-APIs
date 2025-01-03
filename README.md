### Azure Data Factory (ADF) Pipeline Template for Canvas LMS Data Integration
## Overview
This repository contains a template for an Azure Data Factory (ADF) pipeline designed to automate data extraction from the Canvas LMS API and import it into an Azure SQL Database.

## The pipeline leverages:

Web Activity to call the Canvas API and retrieve course data.

Copy Data Activity to store the extracted data in Azure Blob Storage and later insert it into Azure SQL tables.

## Features
End-to-End Pipeline – Automates the process of fetching, transforming, and storing Canvas LMS data.

Scalable and Modular – Easily adaptable for different Canvas LMS endpoints (users, enrollments, assignments).

Linked Services – Supports external services like:

Canvas API for data extraction.

Azure Blob Storage for temporary data storage. (if needed)

Azure SQL Database for final data ingestion.

Configurable – Fully customizable through dataset and linked service parameters.
