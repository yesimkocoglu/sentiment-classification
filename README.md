# Sentiment Classification of Customer Service Conversations

Fine-tuning a BERT-based transformer for 3-class sentiment classification on the **BrownBox customer service dataset**.

## Task
Classify `customer_sentiment` (negative / neutral / positive) from customer-agent conversations.

## Approach
- **Model**: `bert-base-uncased` fine-tuned for sequence classification
- **Preprocessing**: Extract only customer turns (reduces token count, removes noise)
- **Experiment Tracking**: [WANDB Project](https://wandb.ai) *(link will be updated)*
- **Dataset**: ~34,926 train / ~1,153 test conversations

## Project Structure
```
transformer_assign1/
├── train.csv / test.csv
├── requirements.txt
├── notebooks/
│   ├── 01_eda.ipynb          # Exploratory Data Analysis
│   └── 02_train_evaluate.ipynb  # Training + Evaluation (run on Colab)
└── README.md
```

## Setup
```bash
pip install -r requirements.txt
```

## Results
*(To be updated after training)*

| Metric | Value |
|---|---|
| Test Accuracy | - |
| Macro F1 | - |
| Weighted F1 | - |
