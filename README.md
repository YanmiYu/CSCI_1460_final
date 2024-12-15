# CSCI_1460_final
This repository contains the implementation of a Question Answering (QA) system using the DistilBERT model from the Hugging Face transformers library. This system is designed to comprehend text context and provide answers to related questions, mirroring the capabilities demonstrated in the paper, "A BERT Baseline for the Natural Questions." The goal is to replicate the short answer and no answer results discussed in the paper, enhancing our understanding of BERT's application in real-world NLP tasks.

Paper Link: [read paper here](https://drive.google.com/file/d/1TQ3tpsdHQ76pC0g8-aPmhJslo5QSJSTp/view)

## Overview
This project aims to apply the principles of machine learning to natural language processing tasks specifically focused on understanding context and providing concise answers to questions. Our system tests the robustness of the DistilBERT model in identifying pertinent information and discerning when no adequate answer is available within the provided texts.

## Data Description
The dataset used for this project has been curated to align closely with the specific objectives of replicating selected scenarios from the referenced paper. This reduced dataset encompasses only two of the paper's four annotated answer types, which are:
- No answer: Instances where the questions cannot be answered with the provided context.
- Short answer: Questions that have concise answers directly extractable or inferable from the context.

Data Link: [see data here](https://drive.google.com/drive/folders/1JQKrKT_w2PQgrpXw2scvB4fUhl5D4794?usp=sharing)

## Video
Here is the link for the video: 

## Installation
To set up and run the project locally, follow these steps:

# Clone the repository
git clone https://github.com/yourusername/CSCI_1460_final.git

# Navigate to the project directory
cd CSCI_1460_final

# Install required dependencies
pip install -r requirements.txt
