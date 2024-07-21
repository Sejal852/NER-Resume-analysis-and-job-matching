# NER for Resumes Analysis and Matching Job System

This project leverages Named Entity Recognition (NER) to analyze resumes and match them with job descriptions. It utilizes machine learning models and natural language processing techniques to extract relevant information from resumes and assess their compatibility with job requirements.


## Installation

To run this project, you'll need to set up your environment by installing the required packages. You can do this by running the following commands:

```bash
pip install keras tensorflow
pip install sentence_transformers
pip install regex
pip install textdistance
pip install spacy
python -m spacy download en_core_web_lg
```

## Usage

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/NER_for_Resumes_Analysis_and_Matching_Job_System.git
cd NER_for_Resumes_Analysis_and_Matching_Job_System
```

2. **Run the Jupyter notebook:**

```bash
jupyter notebook NER_for_Resumes_Analysis_and_Matching_Job_System.ipynb
```

3. **Follow the steps in the notebook to process resumes and job descriptions.**

## Project Structure

- `NER_for_Resumes_Analysis_and_Matching_Job_System.ipynb`: Main Jupyter notebook containing the project code.
- `data/`: Directory to store input resumes and job descriptions.
- `models/`: Directory to save trained models.

## Key Features

- **NER for Resumes:** Extracts entities such as names, skills, education, and experience from resumes.
- **Job Matching:** Compares resumes with job descriptions to find the best matches based on extracted entities.
- **Similarity Measurement:** Uses TF-IDF and cosine similarity to assess the compatibility between resumes and job descriptions.

## Dependencies

- `tensorflow`
- `keras`
- `sentence_transformers`
- `regex`
- `textdistance`
- `spacy`

