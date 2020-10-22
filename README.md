# Emotion Analysis on OpenSubtitles

In this paper, we present a data-driven approach to the segmentation of subtitles in movie into a speaker-aligned dataset. On this novel dataset, we applied our pre-train BERT model to label the dialogues with emotions. A Social bot was finally trained with our novel dataset in order to catch emotions in text conversations.

The project is organized as follow : 

1. **Preprocessing**
* Load Opensubtitle
* Applied a Basic segmentation to produce a dialogues based dataset 
* Implement two distincts data-driven segmentation

2. **Data Analysis**

Compute basics statistics on:
* The Original Opensubtitle
* The two Automatic segmented subset

3. **Emo_bert_Training.ipynb**  :

Testing our Emo-Bert classifier on our new datasets.

2. **Results_analysis.ipynb** : 

Plot our different analysis and analyse the classification performance with other states-of-the-Art algorithm of Emotion Classification

Related Paper:
”Automatic turn segmentation for Movie & TV subtitles”, P. Lison and R. Meena, (2016)




