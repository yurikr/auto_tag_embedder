# About

Given a multi-modal embedder network that creates a joint representation between images and language attributes, allowing word2vec kind of math for product discovery; the aim of the project is to make the attribute addition and subtraction of the query words easier and more user friendly through auto-suggestion tags.

# Current work

1. Understood the embedder model and several other losses for multi modal search 
2. Collected the iMaterialist Data from kaggle with 228 distinct labels (2000 training images and 500 validation images)
3. Prepared the data to feed into the multi label classifier
4. Built a baseline multi label classifier and recorded performance.

# Next Steps 

1. Make improvements to the baseline model through changing sigmoid thresholds, varying learning rate, experimenting with different pretrained models.
2. Read literature for other techniques for efficient multi label prediction
