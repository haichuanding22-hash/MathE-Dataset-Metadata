# Assessing Mathematics Learning in Higher Education

## General Information

### Dataset Title
Assessing Mathematics Learning in Higher Education

### Project Description
This dataset contains data from the MathE platform, which was developed under the MathE project. It includes 9,546 answers to mathematics questions on topics taught in higher education. The dataset contains information about students and questions, including student country, answer type, question level, topic, subtopic, and keywords.

### Creators
- Beatriz Flamia Azevedo
- M. Fátima Pacheco
- Florbela P. Fernandes
- Ana I. Pereira

**Affiliation:** Polytechnic Institute of Bragança

### README Author

- **Name:** Haichuan Ding
- **ORCID:** [0009-0009-3132-5709](https://orcid.org/0009-0009-3132-5709)

### Data Collection Period
February 2019 to December 2023

### DOI
[10.34620/dadosipb/PW3OWY](https://doi.org/10.34620/dadosipb/PW3OWY)

### Keywords
- Education
- Mathematics learning
- Higher education
- Learning analytics

### Dataset Characteristics
- **Data type:** Tabular
- **Subject area:** Engineering
- **Number of instances:** 9,546
- **Number of features:** 8
- **Feature types:** Real, Categorical, Integer
- **Missing values:** No
- **Associated tasks:** Classification, Regression, Clustering

## Data & File Overview

The dataset contains 9,546 records and 8 features. Each record represents a student's answer to a mathematics question on the MathE platform.

### Dataset File
- **File name:** MathE dataset (4).csv
- **File format:** CSV
- **File size:** Approximately 1 MB
- **Number of records:** 9,546
- **Number of features:** 8

### Variables
The dataset contains the following eight variables:

1. Student ID
2. Student Country
3. Question ID
4. Type of Answer
5. Question Level
6. Topic
7. Subtopic
8. Keywords

A detailed description of these variables is provided in the Data Dictionary section below.

### Missing Data
The dataset has no missing values.

## Sharing & Access Information

### Access
The dataset is publicly available through the UCI Machine Learning Repository.

### DOI
10.34620/dadosipb/PW3OWY

### License
The dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. The data can be shared and adapted as long as appropriate credit is given.

### Recommended Citation
Flamia Azevedo, B., Pacheco, M., P. Fernandes, F., & Pereira, A. (2024). *Assessing Mathematics Learning in Higher Education* [Dataset]. UCI Machine Learning Repository. DOI: 10.34620/dadosipb/PW3OWY.

### Related Publication
Azevedo, B. F., Pacheco, M. F., Fernandes, F. P., & Pereira, A. I. (2024). *Dataset of mathematics learning and assessment of higher education students using the MathE platform*. Data in Brief.

## Methodological Information

### Data Collection
The data were collected through the MathE platform from February 2019 to December 2023. The platform was developed as part of the MathE project to support mathematics learning in higher education.

Each record in the dataset represents a student's answer to a mathematics question. The dataset records whether the answer was correct or incorrect and includes information about the question, such as its level, topic, subtopic, and keywords.

### Question Classification
Questions are classified as either basic or advanced. The question level was assigned by the professor who submitted the question to the MathE platform.

### Data Organization
The collected data are organized in a tabular CSV file. The dataset contains 9,546 records and eight variables. Student and question identifiers are included so that responses can be associated with students and individual questions.

### Data Quality
The UCI Machine Learning Repository reports that the dataset contains no missing values. The variables use defined categories, including correct or incorrect for Type of Answer and basic or advanced for Question Level.

## Data-Specific Information

### Data Dictionary

The dataset contains eight variables. The following table describes the variables and their data types.

| Variable | Type | Description | Values / Categories | Missing Values |
|---|---|---|---|---|
| Student ID | Integer | Identifier assigned to each student | Integer identifier | No |
| Student Country | Categorical | Country associated with the student | Country | No |
| Question ID | Integer | Identifier assigned to each mathematics question | Integer identifier | No |
| Type of Answer | Binary | Indicates whether the student's answer was correct or incorrect | Correct / Incorrect | No |
| Question Level | Categorical | Difficulty level of the mathematics question | Basic / Advanced | No |
| Topic | Categorical | Main mathematical topic of the question | Mathematics topic | No |
| Subtopic | Categorical | More specific mathematical area within the main topic | Mathematics subtopic | No |
| Keywords | Categorical | Keywords associated with the mathematics question | Mathematical keywords | No |

### Number of Observations and Variables

- **Observations:** 9,546
- **Variables:** 8

### Missing Values

The dataset contains no missing values.

### Units of Measurement

Most variables in this dataset are identifiers or categorical variables, so physical units of measurement are not applicable.

## Metadata and Documentation Choices

### Metadata Standard

I chose the Data Documentation Initiative (DDI) as the metadata standard for this project. DDI is designed to describe data used in the social, behavioral, economic, and health sciences. I chose DDI because this dataset contains structured information about students and their learning activities. It provides a useful framework for documenting the dataset, variables, data collection, and access information.

### Template and Software

I used GitHub to create and publish the README file. The README was written in Markdown. I followed the README checklist provided in the course materials to organize the documentation into sections such as general information, data and file overview, sharing and access information, methodological information, and data-specific information.

### Challenges and Solutions

The most challenging part was deciding how much information should be included in the README and how to organize it clearly. Some information was available from the UCI Machine Learning Repository, while other details needed to be identified from the dataset documentation.

To address this, I organized the README according to the course checklist and checked the dataset information from its original sources. I also created a data dictionary to make the variables easier to understand and avoided adding information that could not be confirmed from the dataset documentation.
