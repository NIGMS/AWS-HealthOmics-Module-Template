# HealthOmics scRNAseq Demo

## Overview:
This repository was built for the purpose of introducing AWS HealthOmics and giving an example of converting a workflow to HealthOmics. It covers the topics of what services HealthOmics offers and a step by step guide of converting a scrnaseq nextflow to HealthOmics. 

## Outcomes:
* Create a reference store
* Create a sequence store
* Pushed public containers to ECR 
* Create HealthOmics private workflow

## Requirements:
* AWS Account
* Proper IAM User and Role setup
* Amazon SageMaker Notebook Instance

## Setup:
1. Make check the policies of your SageMaker role and ensure that you have IAMFullAccess
2. Once you are in SageMaker notebook open terminal and cd into the SageMaker directory.<br> 
Then run the command: <br> git clone -b scrnaseq-demo https://github.com/NIGMS/AWS-HealthOmics-Module-Template.git
3. Then change into the scrnaseq-demo folder and make a parameters folder using the command: <br>
mkdir parameters

## Module Order:
1. Review HealthOmics Tutorial
2. HealthOmics ECR Setup
3. HealthOmics Storage Setup
4. HealthOmics Workflow

