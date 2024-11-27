# Analysis of toxicity in Youtube Comments effects on Communities

### Project Overview

This data analysis project aims to provide insights into the effects of toxicity in Youtuber video comments on communities over the past year. By analyzing the frequency and the level of toxicity present in the youtube comments we can use current news and suggestions to provide a conclusion on the effects of toxicity from Youtube comments.

### Data Sources

Youtube Comments: The primary data used for this analysis were youtube comments posted in specific videos uploaded in recent times. It take the first 100 comments of the video containing statements made along with emojis by the individual.

### Tools
- Hugging Face Model [here](https://huggingface.co/s-nlp/roberta_toxicity_classifier)
- Google Collab [here](https://colab.research.google.com/drive/1i0VyNJ7W0KmU8PWuXhE238pYmQl4fh04?usp=sharing)

### Data Cleaning/Preparation
In the initial data preparation phase, we performed:
1. Data loading and inspection
2. Using import emoji to demojize the emojis in the text and turn them to words

Since the Youtube API gives us comments and emojis, there isn't more we need to prepare the data for the model.

### The Final Project for Python for Data Science Class
Using a Huggingface model to build a toxicity classifier, We used Youtube videos to evaluate how toxicity affects communities. In this case it would be the communities of the Youtubers. Youtuber commmunities have been steadily increasing throughout the years because of ease of access to the internet and Youtube being free. We analyze the Youtuber comments and how they affect the Youtubers and their communities.

## For an easier time scrolling, go to the collab. Its table of contents is well organized.
[Direct](https://docs.google.com/document/d/1iYGwOhD8CpG5vGuvcD6cRaDzgDLypck5QD7j0Q8MOh0/edit?usp=sharing)
