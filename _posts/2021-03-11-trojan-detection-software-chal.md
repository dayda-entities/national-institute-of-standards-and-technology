---
title: Trojan Detection Software Challenge - Round 1 Training Dataset
created: '2021-03-11T17:22:19.463363'
modified: '2021-03-11T17:22:19.463372'
state: active
type: dataset
tags:
  - >-
    Trojan Detection Artificial Intelligence Ai Machine Learning Adversarial
    Machine Learning
groups: []
csv_url: 'https://data.nist.gov/od/ds/mds2-2195/METADATA.csv'
json_url: ''
layout: post

---
The data being generated and disseminated is the training data used to construct trojan detection software solutions. This data, generated at NIST, consists of human level AIs trained to perform a variety of tasks (image classification, natural language processing, etc.). A known percentage of these trained AI models have been poisoned with a known trigger which induces incorrect behavior. This data will be used to develop software solutions for detecting which trained AI models have been poisoned via embedded triggers. This dataset consists of 1000 trained, human level, image classification AI models using the following architectures (Inception-v3, DenseNet-121, and ResNet50). The models were trained on synthetically created image data of non-real traffic signs superimposed on road background scenes. Half (50%) of the models have been poisoned with an embedded trigger which causes misclassification of the images when the trigger is present.

Errata: This dataset had a software bug in the trigger embedding code that caused 4 models trained for this dataset to have a ground truth value of 'poisoned' but which did not contain any triggers embedded. These models should not be used.

Models Without a Trigger Embedded: id-00000184 id-00000599 id-00000858 id-00001088 

Google Drive Mirror: https://drive.google.com/open?id=1uwVt3UCRL2fCX9Xvi2tLoz_z-DwbU6Ce
