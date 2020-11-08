# Text-Analytics-Project--Fall-2020
This project addresses the hate speech through building a multimodal classifier on Facebook hateful memes dataset

# Dataset: Customized Facebook hate memes dataset for sarcasm/hateful labels

## code workflow - we have multiple python notebooks for different purposes
1. Pre-processing notebook
2. Data sourcing & EDA notebook
3. Model building & Evalulation notebooks

# Project workflow(Refer to project report)
1. Google API was used to extract the text from Images and stored in a row
2. Various pre-processing techniques were used to solve OCR errors like word segmentation, Internet slang contractions, spelling correction using language models.
3. Conducted exploratory data analysis to understand the data(Used Topic modelling, word frequency plots, Named Entity Recognition using spacy language model, Bigrams & Trigrams to understand the conext of a meme)
4. Used pre-trained fasttext model with urban dictionary embeddings to get better representations of internet slang words
5. Built four models to check which type of model has outperformed others and can be used to improve the current algorithms
6. Insights from our current work and future work 
