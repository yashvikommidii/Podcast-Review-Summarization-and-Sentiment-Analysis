# Podcast-Review-Summarization-and-Sentiment-Analysis
Podcast Review Summarization and Sentiment Analysis is an NLP project that focuses on analyzing user feedback from podcast reviews

This project analyzes user reviews from podcasts to generate short summaries and detect sentiment (positive, neutral, negative). It helps podcast creators understand audience feedback at scale and make informed content decisions.



There are multiple folders in this repo which have different functionalities:
folders: 
1. **Code**: This folder consider the code files of the project, primarily run on VScode.

2. **about**: This folder consists of the document which has all information like introduction, methodology, results documentation.

3. **output files**: This folder consists of the output files which I have produced as a part of project, extracted after running the code.

4. **Data**: it  has info abou the dataset, as we should not upload the dataset, we will just include description on what is the data, how it looks and code for accessing it is in project_code.ipynb.

5. **Proposal.md**: This file has the proposal of the project.

6. **README.md**: This file has the information of which folder has what type of information.

**Project Steps**
1. **Data Cleaning & Preprocessing**: Merged and cleaned 3 JSON files into one dataset.
2. **Summarization**:
   - *TextRank*: Extractive method that picks important sentences.
   - *T5*: Abstractive transformer that generates human-like summaries.
3. **Sentiment Analysis**:
   - *VADER*: Lightweight rule-based analysis.
   - *BERT*: Deep learning model for contextual sentiment.
4. **Evaluation**:
   - Compared BERT sentiment to actual ratings using precision, recall, and F1-score.
   - Checked agreement between BERT and VADER.
5. **Outputs**:
   - Final results saved in output files for reuse or visualization.

## Environment Setup

To install the required packages, run:

```bash
pip install -r requirements.txt
