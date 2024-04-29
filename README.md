# Resume Revealer Extended

The Resume Revealer Extended is an advanced tool designed to extract crucial information from resumes, including skills, education, experience, and even relevant links to institutions and workplaces. This extended version enhances the functionality of the original Resume Revealer by providing additional features to assist recruiters and hiring managers in their candidate evaluation process.

## Overview

The Resume Revealer Extended automates the extraction process, saving valuable time and effort typically spent manually examining resumes. By leveraging various Python libraries and Natural Language Processing (NLP) techniques, this tool parses resumes stored in different formats such as PDF, HTML, DOCX, JPG, and more. It partitions the text into relevant sections, extracts key information, and even identifies job titles based on pre-trained models and industry-standard classifications.

## Features

### 1. Enhanced Information Extraction

- **Skills, Education, and Experience**: Extracts skills, education history, and work experience from resumes.
- **Job Role Extraction**: Identifies potential job roles using tokenization, stop word removal, punctuation removal, and lemmatization.
- **Job Title Identification**: Utilizes pre-trained Word2Vec models to identify job titles within resumes.

### 2. Link Retrieval for Institutions and Workplaces

- **Institutional Links**: Retrieves URLs or contact information for educational institutions mentioned in the resume.
- **Workplace Links**: Provides links or contact details for previous workplaces listed in the resume.

### 3. Seamless Integration

- **Easy Setup**: Simple installation process with Python libraries such as PyPDF2, python-pptx, pytesseract, python-docx, textract, NLTK, and Gensim.
- **Automated Parsing**: Parses resumes stored in a specified directory, facilitating batch processing for efficiency.

## Installation

1. Clone the repository or download the source code.
2. Install the required Python libraries:
   - PyPDF2
   - python-pptx
   - pytesseract
   - python-docx
   - textract
   - NLTK (Natural Language Toolkit)
   - Gensim

## Usage

1. Ensure all required libraries are installed.
2. Place the resumes to be parsed in a designated directory.
3. Run the Resume Revealer Extended script.
4. Review the extracted information, including skills, education, experience, and identified job titles.
5. Retrieve institutional and workplace links for further candidate evaluation.

## Output

The output of the Resume Revealer Extended includes:
- Extracted skills, education, and experience from each resume.
- Identified job titles based on similarity scores and industry-standard classifications.
- URLs or contact information for institutions and workplaces mentioned in the resumes.
