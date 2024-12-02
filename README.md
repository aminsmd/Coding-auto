# Minds and Machines Unite: CPS Classification Repository

This repository contains implementations of various machine learning and deep learning models developed for the classification of Collaborative Problem Solving (CPS) skills, as described in the paper **"Minds and Machines Unite: Deciphering Social and Cognitive Dynamics in Collaborative Problem Solving with AI"**.

## Overview

This project explores the automated classification of CPS skills using multiple models, including traditional machine learning algorithms, deep learning techniques, and large language models (LLMs). The implementation focuses on social and cognitive dimensions of CPS interactions.

## Repository Structure

- **`models/`**:
  - **`bert/`**: Code for fine-tuning and evaluating BERT-based models.
  - **`DL/`**: Implementation of deep learning models such as LSTM, CNN, and hybrid architectures.
  - **`gpt2/`**: Code for fine-tuning and testing GPT-2-based classifiers.
  - **`traditional/`**: Scripts for traditional machine learning models like Random Forest, SVM, and Naive Bayes.
- **`.gitignore`**: Files and directories excluded from version control.
- **`README.md`**: Repository documentation (this file).
- **`requirements.txt`**: List of Python dependencies.

## Dependencies

To set up the environment, install the required Python packages:

```bash
pip install -r requirements.txt
```

Primary Dependencies

	•	tensorflow
	•	torch
	•	transformers
	•	scikit-learn
	•	pandas
	•	numpy

## Usage

Running the Models

Each model implementation is self-contained within its respective directory under models/. Follow the instructions in the script headers or README files within each subdirectory for usage details.

Customization

The repository assumes access to preprocessed data files. Update the paths in the scripts as necessary for local use.

Evaluation

Results are logged during execution and may include performance metrics such as:
	•	Accuracy
	•	F1 Scores: Macro and Weighted
	•	Confusion Matrices

These metrics align with the task-based train-test split methodology discussed in the associated paper.

Key Features

	•	Traditional ML Models: Fast, interpretable baseline methods.
	•	Deep Learning Models: Leverage sequential and contextual features of text data.
	•	Large Language Models: State-of-the-art NLP models (BERT, GPT-2) fine-tuned for CPS classification.

Citation

If you use this repository, please cite the associated publication:

@inproceedings{samadi2024minds,
  title={Minds and Machines Unite: Deciphering Social and Cognitive Dynamics in Collaborative Problem Solving with AI},
  author={Samadi, Mohammad Amin and Jaquay, Spencer and Lin, Yiwen and Tajik, Elham and Park, Seehee and Nixon, Nia},
  booktitle={Proceedings of the 14th Learning Analytics and Knowledge Conference},
  pages={885--891},
  year={2024}
}
