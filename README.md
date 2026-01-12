# Topic Classification with DistilBERT (Mini Project)

This repository is a small hands-on project for AI engineer training.
The focus is not only model training, but also basic ML workflow:
training log review, error analysis, and iterative improvements.

## Goal
- Train a text classification model
- Save and review training logs (loss / accuracy / F1)
- Inspect misclassified examples (errors.tsv)
- Visualize confusion matrix
- Try a simple improvement (class-weighted loss) and compare results

## Notes (AI assistance)
This mini project was developed with strong AI assistance (ChatGPT).
I keep this transparent because the goal is training and iteration practice.

## Dataset
- ver1: `tweet_eval` (sentiment-style labels)
- ver2: `SetFit/bbc-news` (topic classification labels)
- 
Note: Label names differ by dataset. This project includes dataset-specific label handling.

## Model
- distilbert-base-uncased (Hugging Face Transformers)
- Training on macOS (Apple Silicon / MPS)

## What’s included
- Notebook for training and evaluation (`*.ipynb`)
- Training logs (`logs/train_log_*.tsv`)
- Error samples (`results/errors_*.tsv`)
- Confusion matrix image (`results/confusion_matrix_*.png`)

## How to run (high level)
1. Open the notebook
2. Run cells from top to bottom
3. Check `logs/` and `results/` for outputs

## Findings / Notes (work in progress)
Findings depend on the dataset version and experiment settings.
I keep logs (`logs/`) and error samples (`results/errors_*.tsv`) so results are reproducible.
(Analysis notes will be updated per run.)
