# Master Thesis Repository

## Specifications (based on the [Proposal](https://github.com/the-teachingRSE-project/RSE-Masters/blob/main/thesis/ds_thesis.md))

### Objectives

- Collect and preprocess a dataset of existing [RSE syllabi](https://de-rse.org/learn-and-teach/learn/#curricula-on-scientific-computing), computing curriculas [@CC2020;@DSBOK2017;@SWEBOK2014] and related documents.
- Apply data mining and natural language processing (NLP) methods to extract topics and competencies.
- Use topic modelling (e.g., LDA, BERTopic) to identify latent themes relevant to RSE education.
- Map these findings onto an evolving modular curriculum framework.

### Research Questions

- What are the dominant topics in existing RSE-related materials?
- How can topic modelling inform the structure and sequencing of curriculum components?
- What gaps exist between current RSE education and industry demands?

### Methodology

- Use data science tools (e.g., `scikit-learn`, `spaCy`, `BERTopic`) for preprocessing and analysis
- Leverage clustering and dimensionality reduction for curriculum mapping
- Compare generated topic models to existing competence frameworks (e.g., ACM, EOSC)

### Expected Outcomes

- A corpus of annotated RSE-related materials
- A topic map visualizing core and peripheral RSE themes
- A mapping of RSE-modules to respective topics/mater

## Work Packages

### 1 Data Aquisition
- look for official downloads
- ask the universities for an export file
- last option: webcrawler
### 2 Data Processing
- filter the data
- develop structured dataset
    - module name
    - module content description
    - competence description
    - context (university name etc.)
### 3 Topic Modelin/NLP
- visualizing core and peripheral RSE themes