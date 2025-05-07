# POS Tagging Using Hugging Face Transformers with Arabic Dataset

This project focuses on developing a Part-of-Speech (POS) tagging model for the Arabic language by fine-tuning pre-trained transformer models from Hugging Face. It includes data preprocessing, model training, evaluation, and hyperparameter tuning.

## 📁 Repository Structure

- `POS_Tagging_Notebook.ipynb`: Main notebook demonstrating the end-to-end pipeline.
- `Model/`: Scripts for model construction and training.
- `Tokenization/`: Utilities for tokenizing Arabic text and aligning tags.
- `README.md`: Project description and usage instructions.

## 📊 Project Overview

- **Goal**: Build an Arabic POS tagger using transformer-based models.
- **Models**: Fine-tunes models like `bert-base-arabic` from Hugging Face.
- **Features**:
  - Handles subword tokenization for Arabic.
  - Aligns POS tags with subword tokens.
  - Evaluates using precision, recall, F1-score, and accuracy.
  - Includes hyperparameter tuning for optimization.

## 🛠️ Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mohamedsalama677/POS-Tagging-Using-Hugging-Face-Transformers-with-Arabic-Dataset.git
   cd POS-Tagging-Using-Hugging-Face-Transformers-with-Arabic-Dataset
   ```

2. **(Optional) Create and activate a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 📈 Usage

1. **Prepare Data**:
   - Ensure input data consists of Arabic sentences and their corresponding POS tags.
   - Use the tokenization utilities to preprocess text and align labels.

2. **Train the Model**:
   - Run `POS_Tagging_Notebook.ipynb` to start training with preprocessed data.
   - The notebook supports multiple models and hyperparameters.

3. **Evaluate the Model**:
   - Model is evaluated on validation and test sets.
   - Outputs accuracy, precision, recall, and F1-score.

4. **Tune Hyperparameters**:
   - Use `hyperparameter_tuning()` to try different learning rates, batch sizes, and epochs.
   - Select the best configuration based on validation accuracy.

5. **Save Final Model**:
   - The trained model and tokenizer are saved locally for deployment or reuse.

## 🧪 Output

- Saved model checkpoints and tokenizer.
- Printed metrics on validation and test sets.
- Model comparison results (if using multiple architectures).

## 📬 Contact

For any questions, feel free to reach out to [mohamedsalama](mailto:mohamedsalama152019@gmail.com).
