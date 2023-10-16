# NLP-based music processing for composer classification project
This repository contains the code and resources for our paper titled "NLP-based Music Processing for Composer Classification." In this work, we explore the application of Natural Language Processing (NLP) techniques to the domain of music analysis, specifically for the classification of composers based on their musical compositions. By leveraging NLP and machine learning, we aim to contribute to the field of musicology and automate the task of composer identification.

## Abstract
Categorizing music pieces by composer is a challenging task in digital music processing due to their highly flexible structures, introducing subjective interpretation by individuals. This research utilized musical data from the MIDI and audio edited for synchronous tracks and organization dataset of virtuosic piano pieces. In this work, pitch and duration were the musical features of interest. The goal was to innovate an approach to representing a musical piece using SentencePiece and Word2vec, which are natural language processing-based techniques. We attempted to find correlated melodies that are likely to be formed by single interpretable units of music via co-occurring notes, and represented them as a musical word/subword vector. Composer classification was performed in order to ensure the efficiency of this musical data representation scheme. Among classification machine learning algorithms, k-nearest neighbors, random forest classifier, logistic regression, support vector machines, and multilayer perceptron were employed to compare performances. In the experiment, the feature extraction methods, classification algorithms, and music window sizes were varied. The results were that classification performance was sensitive to feature extraction methods. Musical word/subword vector standard deviation was the most effective feature, resulting in classification with a high F1-score, attaining 1.00. No significant difference was observed among model classification performances.

## Dataset
The data including MIDI files and CSV file (maestro-v3.0.0.csv) that were used to carry out this research is publicly available from https://magenta.tensorflow.org/datasets/maestro [Hawthorne et. al., 2019]


## Citation

If you find our work helpful or use any part of this repository in your research, please consider citing our paper:

```
@article{deepaisarn2023nlp,
  title={NLP-based music processing for composer classification},
  author={Deepaisarn, Somrudee and Chokphantavee, Sirawit and Chokphantavee, Sorawit and Prathipasen, Phuriphan and Buaruk, Suphachok and Sornlertlamvanich, Virach},
  journal={Scientific Reports},
  volume={13},
  number={1},
  pages={13228},
  year={2023},
  publisher={Nature Publishing Group UK London}
}
```

We are excited to share our research and collaborate with fellow researchers and music enthusiasts in advancing the field of music analysis and NLP

Copyright © 2022 Somrudee Deepaisarn, Sirawit Chokphantavee, Sorawit Chokphantavee, Phuriphan Prathipasen, Suphachok Buaruk and Virach Sornlertlamvanich are authors of this computer program, contributed to the project 'NLP-based music processing for composer classification' All right reserved.
