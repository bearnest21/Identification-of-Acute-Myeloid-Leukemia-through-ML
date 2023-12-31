# Identification of Acute Myeloid Leukemia through ML

## Team members: 

-Ben Earnest

-Andrew Kim

-Gabriella Rivera

## Company Name: Blood Cancer Research (BCR)
## Company Industry: Drug Research
## Company Size: 200 Employees

## Background: 
Our group represents Blood Cancer Research (BCR), a non-profit institute aiming to discover novel drug targets against various hematologic cancers. We have been tasked by the U.S. Department of Health & Human Services to research target proteins and develop novel drugs that disrupt pathways connected to progression of Acute Myeloid Leukemia (AML). 

## Objective:
The goal is to create a predictive model that can determine AML protein of interest through identification of protein-protein interactions. In doing so, we propose to build a machine learning algorithm that identifies AML key proteins from data sets derived from Chan Zuckerberg’s Biohub OpenCell database and the Cancer Target Discovery and Development Data Portal’s Beat AML program. This is also done to support the effort to advance blood cancer exploratory work with the intent to increase blood cancer survival rate through enhanced drug target repertoire.

## Non-objective:
Blood Cancer Research is not intentionally classifying characteristics that potentially create biased representation against groups of people. Any patient information is anonymized. The creation of the ML model is only intended to identify potential proteins of interest. Identified proteins need further rigorous scientific and clinical research peer review. 

## Datasets:
OHSU_BeatAMLWaves_1_2_ClinicalSummary & opencell_protein_interactions csv files. 

Data sources will come from the Chan Zuckerberg Biohub OpenCell database and Beat AML program derived from the Cancer Target Discovery and Development Data Portal. The tables range from 11kB to 4.6MB of data sets. The data, once uploaded as CSV files, will then be uploaded and stored in both Github and in Amazon S3. A bucket will be created and specified within AWS region before the data is uploaded to the specified bucket as objects in S3.

## Data Sources:
https://ocg.cancer.gov/programs/ctd2/data-portal 

https://opencell.czbiohub.org/download 

## Description of datasets:
The Beat AML Clinical Summary data set features 159 attributes, which comprises a collection of patient information from 672 tested tumor specimens to address analysis pertaining to clinical, genomic, transcriptomic, and functional biology of AML. For the initiating purpose of identifying AML, we will be using only 18 attributes to bucket and analyze. Our second data set, OpenCell Protein Interaction data set, features nine attributes, which will be retained for the duration of our project.

The tables range from 11kB to 4.6MB of datasets. The data as CSV files will be uploaded and stored in a Github repository. The data will also be stored in Amazon S3, which will involve creating and specifying a bucket within Amazon Web Services (AWS) Region before the data is uploaded to the specified bucket as objects in S3.

## Programming Languages:
AWS Cloud Computing Services (SageMaker Studio, S3, Athena, IAM, Glue Crawler), Python through Sagemaker
