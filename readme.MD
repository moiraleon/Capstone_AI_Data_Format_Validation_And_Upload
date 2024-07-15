# Capstone AI Data Validation and Fine-Tuning

This repository contains scripts and Jupyter Notebooks to validate capstone project data, count tokens, estimate costs, and fine-tune an OpenAI model. This project was used for my 2024 Purdue undergraduate capstone.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
  - [Clone the Repository](#clone-the-repository)
  - [Set Up Virtual Environment](#set-up-virtual-environment)
  - [Install Dependencies](#install-dependencies)
- [Data Preparation](#data-preparation)
- [Running the Jupyter Notebooks](#running-the-jupyter-notebooks)
  - [Token Counting](#token-counting)
  - [Data Warnings Analysis](#data-warnings-analysis)
  - [Cost Estimation](#cost-estimation)
- [Uploading the Training File](#uploading-the-training-file)
- [References](#references)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is designed to help you validate your capstone project data, count tokens, estimate costs, and prepare the data for fine-tuning a machine learning model using OpenAI's API. The repository includes Jupyter Notebooks that walk you through these steps interactively.

## Setup

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/capstone-ai-data-validation.git
cd capstone-ai-data-validation
```

### Set Up Virtual Environment

It's recommended to use a virtual environment to manage dependencies. Create and activate a virtual environment using the following commands:

```bash
python3 -m venv myenv
source myenv/bin/activate
```

### Install Dependencies

Install the necessary Python libraries:

```bash
pip install -r requirements.txt
```

## Data Preparation

Place your dataset in the `data` directory. Ensure your dataset is named `mvp_dataset.json` and follows the expected format.

## Running the Jupyter Notebooks

### Token Counting

Open and run the `Token_Counting_for_Capstone_Data.ipynb` notebook to count the tokens in your dataset. This helps ensure your dataset is within the allowable token limits for fine-tuning.

### Data Warnings Analysis

Open and run the `Data_Warnings_Analysis.ipynb` notebook to analyze your dataset for potential issues and log any warnings. This ensures the quality of your data before proceeding with the fine-tuning process.

### Cost Estimation

Open and run the `Cost_Estimation.ipynb` notebook to estimate the costs of fine-tuning and inference based on the total token count in your dataset. This helps you budget and plan for the expenses associated with your project.

## Uploading the Training File

Follow these steps to upload your training file and initiate the fine-tuning process:

1. **Set Up Your OpenAI API Key**:
   Make sure you have your OpenAI API key ready. You can find it in your OpenAI account dashboard.

2. **Upload the Training File**:
   Use the provided script in the `Upload_Training_File.ipynb` notebook to upload your training file and initiate the fine-tuning process.

3. **Monitor the Fine-Tuning Process**:
   Use the provided script to monitor the status of your fine-tuning job.

4. **Use the Fine-Tuned Model**:
   Once the fine-tuning process is complete, use your fine-tuned model to generate responses.

## References

This project was inspired by and utilizes steps from the following resources:

- OpenAI Cookbook: [Chat Fine-Tuning Data Preparation](https://github.com/openai/openai-cookbook/blob/main/examples/Chat_finetuning_data_prep.ipynb)
- OpenAI Documentation: [Preparing Your Dataset](https://platform.openai.com/docs/guides/fine-tuning/preparing-your-dataset)

## Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
```

### Summary

This updated README provides a comprehensive overview of your project, including setup instructions, how to run the Jupyter Notebooks for token counting, data warnings analysis, cost estimation, and uploading the training file for fine-tuning.