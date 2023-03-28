# Building AML with an Exploratory Machine Learning Model

## Team members:

-Ben Earnest

-Andrew Kim

-Gabriella Rivera

## Background: 
Our group represents Blood Cancer Research (BCR), a non-profit institute aiming to discover novel drug targets against various hematologic cancers. We have been tasked by the U.S. Department of Health & Human Services to research target proteins and develop novel drugs that disrupt pathways connected to progression of Acute Myeloid Leukemia. (AML). 

## Objective:
The goal is to build a predictive model that can determine AML protein of interest through identification of protein-protein interactions. In doing so, we propose to build a machine learning algorithm that identifies AML key proteins from data sets derived from Chan Zuckerberg’s Biohub OpenCell database and the Cancer Target Discovery and Development Data Portal’s Beat AML program. 


## Datasets:
OHSU_BeatAMLWaves_1_2_ClinicalSummary & opencell_protein_interactions csv files. 
*Note: We will be using two datasets for our project.
Source data will come from the Chan Zuckerberg Biohub OpenCell database and Beat AML program derived from the Cancer Target Discovery and Development Data Portal.

## Description of datasets:
The Beat AML Clinical Summary data set features 159 attributes, which comprises a collection of patient information from 672 tested tumor specimens to address analysis pertaining to clinical, genomic, transcriptomic, and functional biology of AML. For the initiating purpose of identifying AML, we will be using only 18 attributes to bucket and analyze. Our second data set, OpenCell Protein Interaction data set, features nine attributes, which will be retained for the duration of our project.

The tables range from 11kB to 4.6MB of datasets. The data as CSV files will be uploaded and stored in a Github repository. The data will also be stored in Amazon S3, which will involve creating and specifying a bucket within Amazon Web Services (AWS) Region before the data is uploaded to the specified bucket as objects in S3.

## Programming Languages:
AWS Cloud Computing Services (SageMaker Studio, S3, Athena, Glue Crawler), Jupyter Notebooks/Python
