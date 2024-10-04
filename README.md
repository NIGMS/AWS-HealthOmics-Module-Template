# HealthOmics fastqc Demo

## Overview:
This repository was built for the purpose of introducing AWS HealthOmics and giving an example of converting a workflow to HealthOmics. It covers the topics of what services HealthOmics offers and a step by step guide of converting a fastqc nf-core nextflow pipeline to HealthOmics. 

## Outcomes:
* Build and push public containers to ECR
* Create HealthOmics private workflow and run
* Create a reference store (Optional)
* Create a sequence store (Optional)

## Requirements:
* AWS Account
* Proper IAM User and Role setup
* Amazon SageMaker Notebook Instance in **us-east-1 region**

## Setup:
1. Check the policies of your SageMaker role and ensure that you have IAMFullAccess
2. Once you are in SageMaker notebook open terminal and cd into the SageMaker directory.<br> 
Then run the command: <br> git clone -b fastqc-demo https://github.com/NIGMS/AWS-HealthOmics-Module-Template.git
3. Then cd into the fastqc-demo folder and begin going through the modules according to the order suggested below.

## Module Order:
1. Review HealthOmics Tutorial (Optional)
2. HealthOmics ECR Setup
3. HealthOmics Workflow
4. HealthOmics Storage Setup (Optional)

