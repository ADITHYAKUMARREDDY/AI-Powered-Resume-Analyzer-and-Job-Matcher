# AI-Powered Resume Analyzer and Job Matcher

A Python-based tool designed to run on Google Colab, enabling parsing of resumes and job descriptions (JD) in PDF or DOCX formats. It extracts key information and calculates match percentages between candidates and job requirements. Additionally, the tool integrates with Anthropic's Claude AI for querying candidates' data.

## Features

- Extracts key information from resumes:
  - Candidate name
  - Education
  - Skills
  - Mobile number
  - Email addresses
- Extracts keywords from job descriptions.
- Matches candidate skills with job requirements and calculates match percentages.
- Enables querying candidates' data using AI (Claude integration).
- Supports PDF and DOCX files for both resumes and job descriptions.

## Prerequisites

Before using this tool on Google Colab, ensure you have:

- A valid Anthropic Claude API key.
- Access to Google Colab.
- Required Python libraries installed in the Colab environment.

## Setup and Usage on Google Colab

1. Open the Colab notebook:
   - Upload the `main.py` code to a new notebook or paste it into a cell.

2. Install the required dependencies by running:
   ```bash
   !pip install anthropic docx2txt PyPDF2 spacy nltk
   !python -m spacy download en_core_web_sm



Download necessary NLTK data:

import nltk
nltk.download('stopwords')
nltk.download('punkt')


## Setup and Usage on Google Colab

3. Replace the placeholder `api_key` with your valid Anthropic Claude API key in the script.

4. Run the script:
   - Follow the instructions to upload the Job Description and resumes in PDF or DOCX formats.
   - View extracted data and match percentages for each candidate.
   - Use the query system to ask questions about candidates' data.

### Example Query System

You can ask questions like:
- "Who has the highest match percentage?"
- "Which candidates have Python and SQL skills?"
- "Who has an MBA qualification?"

## Repository

Access the project code on GitHub: [AI-Powered-Resume-Analyzer-and-Job-Matcher](https://github.com/ADITHYAKUMARREDDY/AI-Powered-Resume-Analyzer-and-Job-Matcher.git)

## Contribution

Contributions are welcome! If you encounter any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## Author

**Adithya Kumar Reddy**  
Final Year Computer Science Student, VIT Vellore
