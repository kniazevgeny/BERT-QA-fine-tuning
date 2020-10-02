# BERT fine-tuning for QA

all information about bert you can find [here](https://github.com/google-research/bert)

## What to do
##### Run [jupyter notebook](https://colab.research.google.com/drive/1QV6Kcnr7B4nz8a02bO2neE4X-ikeJnqU?usp=sharing) on colab to fine-tune BERT for QA on russian dataset or to test your own examples

## Files description
#### dev.json, train.json, dev-mini.json & train-mini.json

That's the train and test (80% train, 20% test or dev) parts of sberbank's russian QA dataset. 

To simply train model on your dataset use structure, similar to train.json

Train + dev = 50333 exapmles

Train-mini + dev-mini = 12000 examples

#### model.ckpt-*
This is fine-tuned BERT model for QA

