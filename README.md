# BBC News Text Classification (Mini Project)

This repository is a small hands-on project for AI engineer training.
The focus is not only model training, but also basic ML workflow:
training log review, error analysis, and iterative improvements.

## Goal
- Train a text classification model
- Save and review training logs (loss / accuracy / F1)
- Inspect misclassified examples (errors.tsv)
- Visualize confusion matrix
- Try a simple improvement (class-weighted loss) and compare results

## Dataset
- BBCNews-related text classification dataset
- Labels: negative / neutral / positive

## Model
- distilbert-base-uncased (Hugging Face Transformers)
- Training on macOS (Apple Silicon / MPS)

## What’s included
- Notebook for training and evaluation (`*.ipynb`)
- Training logs (`logs/train_log_*.tsv`)
- Error samples (`results/errors_*.tsv`)
- Confusion matrix image (`results/confusion_matrix_*.png`)

## Notes (AI assistance)
This mini project was developed with strong AI assistance (ChatGPT).
I do not hide this, because the project is part of training and iteration practice.

## How to run (high level)
1. Open the notebook
2. Run cells from top to bottom
3. Check `logs/` and `results/` for outputs

## Findings (short)
- Many errors concentrate around the `neutral` label, which can be ambiguous.
- Class-weighted loss is a simple option to reduce imbalance-related bias.
- Validation metrics and error inspection were more informative than training loss alone.
