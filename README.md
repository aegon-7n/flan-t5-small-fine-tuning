# Question Answering Text Generation Model

This project implements a text generation model using the Hugging Face Transformers library.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/aegon-7n/flan-t5-small-fine-tuning.git
cd flan-t5-small-fine-tuning
```
2. Install dependencies:
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
## Usage
Run the inference script:
```bash
PYTHONPATH=$(pwd) python scripts/run_inference.py
```
## Features
Text generation using fine tuned flan-t5-small model
Interactive command-line interface
Customizable generation parameters

## Model Details
The model used in this project is based on [GlebNoNeGolubin/results.](https://huggingface.co/GlebNoNeGolubin/results)
