# <img src=https://cdn-icons-png.flaticon.com/512/4221/4221412.png height=70 width=80> Movie Review Sentiment Analysis

This project was carried out by Anaconda environment with python 3.9 and [Weights & Biases (WandB)](https://wandb.ai/site) API support.
>[!IMPORTANT]
> To run the notebook, you need to have Anaconda installed (preferrably with CUDA Toolkit and compatible CuDNN).
> run the commands underneath `CREATE CONDA ENVIRONMENT` section to have the same working environment as me.
> When running for the first time, you will need to run the commands underneath `INSTALLING DATA` section to install the data from kaggle. There's no need to run them again unless they are not stored locally (in cases like working in colab).

>[!CAUTION]
> If you decided to not run the conda commands within same notebook or project folder (but in anaconda prompt, for example), you need to copy the `env.yml` full path in the command.
> API KEY to WandB are stored as environment variables, so you should replace them with your own API KEY if needed. Or simply check the plots [here](https://wandb.ai/SoloWork/Movie%20Review%20Sentiment%20Classification%20with%20Tranformers?nw=nwuserkatherineashraf) if you don't intend to train.

**Dataset:**
- I used [IMDB Movie Review Dataset of 50k review](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) from kaggle.
- Where every row have a review and its sentiment of `positive` and `negative` reviews.

**Concerning Notebook:**
- This is a small project of movie reviews classification using various Transformers from HuggingFace. 
- I used Trainer API to train with pytorch.
- I used BERT, Distil-BERT, RoBERTa, and Electra all of Sequence Classification Models.
- All necessary plots are generated in the notebook as well as observation in the `FINAL EVALUATION` section.
