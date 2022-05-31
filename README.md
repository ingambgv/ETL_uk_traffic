# ETL for UK traffic accident EDA

## Overview
An local ETL pipeline to perform EDA on uk traffic accident information. The original idea isn't mine. I got the ETL pipeline schema from job application technical test where they ask to create a ETL using kaggle API for extract the uk_traffic dataset, select the last years from the dataset, load the resulting csv file into a Postgres database and create several plot to get insights from dataset. My original contribution is to use PySpark for the transform step and use pandas built-in plot functions for EDA.

## Comming soon:

1) Use tox module for installing all modules used in the ETL.
2) Orchestrate the extract function.
3) Change transform step code to a SQL-like queries. It will be more easy to read and understand.
4) Connect Postgres database to PowerBI to generate the same plots.
5) Add exceptions to each ETL step. 
