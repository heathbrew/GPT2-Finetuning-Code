# GPT2-Finetuning-Code

This repository contains code and research notebooks for fine-tuning and evaluating GPT-2 models, including both a base model and an IMDb-finetuned variant. The code demonstrates model loading, text generation, and quantitative/qualitative evaluation techniques, as well as the fine-tuning process with training graphs.

## Folder Structure

- **README.md**: This documentation file.
- **install_venv.sh**: A shell script to create and activate a virtual environment and install the required libraries.
- **requirements.txt**: Lists the Python packages needed to run the project.
- **Research/1.Base.ipynb**: A Jupyter notebook demonstrating base imports, dataset loading, and preliminary exploration.
- **Research/1.Calling base Model.ipynb**: A Jupyter notebook that loads the fine-tuned and base GPT-2 models, generates sample texts, and performs evaluations.

## File Paths and Contents

- **Research/1.Base.ipynb**  
  Contains code cells to:
  - Import libraries (e.g., `os`, `torch`, `matplotlib.pyplot`, etc.)
  - Change directory paths to locate data and other project files.
  - Load the IMDb dataset using Hugging Face's `datasets` library.
  - Display the dataset structure and sample entries.

- **Research/1.Calling base Model.ipynb**  
  Demonstrates:
  - Loading the IMDb-finetuned GPT-2 model and generating text from a prompt.
  - Switching to the base GPT-2 model, generating text, and comparing outputs.
  - Instructions and outputs that detail the sample generations and model responses.

