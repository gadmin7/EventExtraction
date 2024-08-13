# Closed Domain Event Extraction on RAMS Dataset

## Abstract

Event Extraction aims to obtain a structured representation of events from unstructured text data. This process involves detecting event instances in texts and identifying the event type along with its participants and attributes. This project focuses on applying deep learning methods for event extraction on the RAMS (Role Across Multiple Sentences) dataset. The RAMS dataset features a diverse set of roles and examples with gold arguments spread across different sentences from event triggers, making it suitable for analyzing both intra-sentence and cross-sentence argument extraction.

In this project, we convert event trigger identification and classification, as well as argument detection, into token classification problems using BIO tagging. We then apply BERT-based models for token classification.

## Dataset

- **Source:** Multi-Sentence Argument Linking (Ebner et al., ACL 2020)
  - [Paper Link](https://aclanthology.org/2020.acl-main.718.pdf)
  - [Dataset Link](https://nlp.jhu.edu/rams/)

- **Description:** 
  The RAMS dataset consists of 9,124 annotated events from news articles, based on an ontology with 139 event types and 65 roles. The dataset includes annotations within a 5-sentence window around each event trigger, marking the closest argument span for each role.

## Project Overview

The project involves several components:

1. **Data Preparation:** Preprocessing of the RAMS dataset and conversion into token classification format using BIO tagging.
2. **Model Training:** Fine-tuning of DistilBERT for event trigger identification and classification.
3. **Evaluation:** Assessing model performance and accuracy.



