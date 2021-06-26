---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Tech. in Computer Science and Communication, Manipal Academy of Higher Education, 2020
* M.S. in Computer Science, University of Illinois at Urbana Champaign, 2022

Work experience
======

* August 2020 - August 2021 : Data Scientist - Applied Research
  * UnitedHealth Group
  * Built a Question Answer Scoring system using Bi-LSTMs and handcrafted features for automatically scoring Request for Proposals.
  * Created ICD embeddings using BERT and used it to predict emergency room visits as a downstream task, bringing down false positives by 40%.
  * Built a One Function Text Classification engine to lower the entry barrier for using Transformer based models.
  * Created an anti-fraud system using Machine Learning to predict aberrant transactions within patients and pharmacies. Built a robust system that concurrently makes inference on upto 1 billion transactions by optimizing memory footprint and time taken down to a third of it's previous value.
  * Built an OCR + NLP Pipeline for managing medical contracts, making real time predictions on upto 100,000 documents.


* Since 2019: NLP Research Assistant
  * Multimodal Digital Media Analysis Lab - IIIT Delhi
  * Created a public dataset and modeled it using a Medium-Specific Language Model to classify tweets as either arecollectionof sexual harassment, or adiscussionon the #MeToo movement.  Presented my work as a long paper at ACL 2019.  Work done in collaboration with Bloomberg New York.
  * Augmented text classification models for Hate Speech Detection by adding Graph Embeddings to modelcommunity interaction and add an extra signal for prediction of hateful content within Arabic Tweets.  Presentedour work atACM Hypertext 2019andACL-SRW 2019.
  * Created novel augmentation techniques for text and speech by exploiting hidden space interpolations.  Presentedour work atCOLING 2020andINTERSPEECH 2020.Work done in collaboration withMIT CSAIL.
  * Supervisor : Dr Rajiv Ratn Shah


  
Skills
======
* Machine Learning
* Natural Language Processing
  * Computational Social Science
  * Data Augmentation
* Software Development

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

