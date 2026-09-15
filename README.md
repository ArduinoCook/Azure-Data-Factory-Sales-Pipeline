# Azure-Data-Factory-Sales-Pipeline
Azure Data Factory pipeline that copies sales transaction data from Azure Blob Storage to Azure SQL Database

## Project Overview

This project demonstrates an Azure Data Factory pipeline that moves sales transaction data from a CSV file stored in Azure Blob Storage into an Azure SQL database.

## Pipeline Architecture

SalesTransactions.csv, -> Azure Blob Storage, -> Azure Data Factory, -> Azure SQL Database.

## Technologies used

* Azure Data Factory
* Azure Blob Storage
* Azure SQL Database 
* GitHub

## Screenshots

## 1. Azure resources

![Azure resources](Azure%20Data%20Pipelines%20Screen%20Prints/01-Azure-Resources.png)

![ADF pipeline source](Azure%20Data%20Pipelines%20Screen%20Prints/02-ADF-Pipeline-Source.png)

![Azure resources](Azure%20Data%20Pipelines%20Screen%20Prints/03-ADF-Pipeline-Sink.png)

![Azure resources](Azure%20Data%20Pipelines%20Screen%20Prints/04-ADF-Pipeline-Success.png)

![Azure resources](Azure%20Data%20Pipelines%20Screen%20Prints/05-Azure-SQL-SalesTransactions-Data.png)

## What I learned

* How to connect Blob Storage to ADF and use a copy activity.
* Schema and mapping basics for CSV to SQL.
* Importance of exact file naming in documentation.

## Project files

* [SalesTransactions.csv](SalesTransactions.csv)

Sample source data used by the Azure Data Factory pipeline.

