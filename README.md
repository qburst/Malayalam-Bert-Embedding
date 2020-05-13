# Malayalam-Bert-Embedding
## Pre-training

Google BERT model pre-trained on Malayalam Common-Crawl Dataset https://github.com/qburst/common-crawl-malayalam.
The model is trained using run_pretraining.py script from https://github.com/google-research/bert.

## Fine-tuning

The pre-trained BERT model was further fine-tuned for a SWAG like task. It was trained for completing a sentence 
from the previous sentence and four given choices. This task is trained as a binary classification problem with the run_classifier.py
 script from https://github.com/google-research/bert.
 
