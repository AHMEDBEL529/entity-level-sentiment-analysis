Overview
========

This notebook is designed to analyze comments from [this YouTube video](https://www.youtube.com/watch?v=VzjoHtYN05k&t=3027s) with the goal of performing entity-level sentiment analysis on all participants in the debate. The objective is to identify which group gained the most positive impressions. To achieve this, I have integrated two pre-trained models from Hugging Face: one for Named Entity Recognition (NER) and another for sentiment classification using one-shot classification. By combining these models into a pipeline, the aim is to gain insights into the general sentiment or opinion expressed towards different entities participating in the video discussion.

Architecture
========

 <p align="center">
  <img src="images/architecture.png" alt="Ports">
  </p>

