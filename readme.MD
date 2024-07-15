# Capstone Data Validation and Fine-Tuning Preparation

This repository contains scripts and notebooks to validate capstone project data, count tokens, and prepare data for fine-tuning an OpenAI model. This project was used for my 2024 Purdue undergraduate capstone.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
  - [Clone the Repository](#clone-the-repository)
  - [Set Up Virtual Environment](#set-up-virtual-environment)
  - [Install Dependencies](#install-dependencies)
- [Data Preparation](#data-preparation)
- [Running the Jupyter Notebook](#running-the-jupyter-notebook)
- [Token Counting](#token-counting)
- [Fine-Tuning the Model](#fine-tuning-the-model)
- [References](#references)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is designed to help you validate your capstone project data, count tokens, and prepare the data for fine-tuning a machine learning model using OpenAI's API. The repository includes a Jupyter Notebook that walks you through these steps interactively.

## Setup

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
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

Place your dataset in the `data` directory. Ensure your dataset is named `your_dataset.json` and follows the expected format.

## Running the Jupyter Notebook

To interactively validate your data and prepare it for fine-tuning, run the Jupyter Notebook:

```bash
jupyter notebook
```

Open the `fine_tuning.ipynb` notebook from the `notebooks` directory and follow the steps provided.

## Token Counting

The Jupyter Notebook includes steps to count tokens in your dataset. Token counting is crucial for understanding the size of your data and ensuring it meets the requirements for fine-tuning with OpenAI's API.

## Fine-Tuning the Model

The notebook guides you through the process of:
1. Loading and preprocessing your dataset.
2. Converting your dataset to JSONL format.
3. Uploading the training file to OpenAI.
4. Initiating the fine-tuning process.
5. Monitoring the fine-tuning job.
6. Using the fine-tuned model to generate responses.

## References

This project was inspired by and utilizes steps from the following resource:

- OpenAI Cookbook: [Chat Fine-Tuning Data Preparation](https://github.com/openai/openai-cookbook/blob/main/examples/Chat_finetuning_data_prep.ipynb)

## Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.