# Sentence-Correction-using-Recurrent-Neural-Networks
Social media is one of the most powerful platforms where people communicate with each other by creating and exchanging their ideas in a virtual network. Thus ML/DL models use these texts/data to determine the emotions, behavior and many other such NLP related tasks.
The standard English is used to train these models for NLP related tasks. But very often in fact most of the times people use short forms/abbreviations in their texts which might not be helpful to train these models or perform an NLP tasks. Changing the texts from non-standard English to Standard English will help increase the performance of many NLP based models. Here, the non-standard English or the one that use short forms/abbreviations is a subset of target data and thus we try to convert these texts to Standard English while preserving the semantic meaning of the texts.

# Deep Learning Problem -
Recurrent Neural Networks have been shown to be more adept in capturing the high-level dynamics of the English language and long-range dependencies. We thus use RNNs as hidden units to convert non-standard English SMS texts to Standard English SMS texts while preserving the semantic meaning of the texts for the sole purpose of increasing the performance of the NLP models.

# Data Explanation –
The dataset to be used for this deep learning problem is publicly available.
https://www.comp.nus.edu.sg/~nlp/corpora.html
This dataset consists of around 2000 SMS texts where for every text we have non-standard English version, standard
English version, and Chinese version. For our problem we are going to use only the non-standard English version and
standard English version.
