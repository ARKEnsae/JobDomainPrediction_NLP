# NLP for Job Domain Prediction  <img src="Rapport/img/LOGO-ENSAE-avatar.png" align="right" alt=""  width="100"/>

Projet for the end of term for the  Machine Learning course for Natural Language Processing (ENSAE 3A) @antuki @AQLT

Using different NLP models we predicted jobs' domains using job descriptions provided by French governmental agencies (Pôle Emploi and Onisep). The different models used are : 

- a model for which we used [pre-trained word-embeddings](https://fauconnier.github.io) to perform data classification using SVM

- recurrent neural networks of type *Long short-term memory* (LSTM) where we use, or not, word-embeddings.

- a pre-trained CamemBERT (French equivalent of BERT) model which uses a bidirectional *transformer*, which is adapted in particular for sequence classification (`BertForSequenceClassification`).

The report is available [here](https://arkensae.github.io/JobDomainPrediction_NLP/Rapport/JobDomainPrediction_NLP.pdf) and the Python code, which can be directly read with Google Colab, is available [here](https://github.com/ARKEnsae/JobDomainPrediction_NLP/blob/main/JobDomainPrediction_NLP.ipynb)

****

Projet de fin de semestre pour le cours de Machine Learning for Natural Language Processing (ENSAE 3A) @antuki @AQLT

Nous avons utilisé des modèles de NLP pour prévoir le domaine d'un emploi (grand domaine de l'arborescence ROME) à partir de sa description (données de Pôle Emploi et de l'Onisep). Pour cela nous avons implémenté plusieurs modèles :

- un modèle SVM qui s'appuie sur une représentation vectorielle des phrases construite grâce à un modèle [pré-entrainé word2vec](https://fauconnier.github.io)

- des modèles de réseaux de neurones récurrents de type *Long short-term memory* (LSTM) qui utilisent, ou non, les représentations vectorielles des mots.

- un modèle de langage pré-entrainé CamemBERT (équivalent français de BERT), qui utilise une architecture bidirectionnelle de *transformer*, qui s'adapte en particulier à la classification de séquences (`BertForSequenceClassification`).

Le rapport est disponible [ici](https://arkensae.github.io/JobDomainPrediction_NLP/Rapport/JobDomainPrediction_NLP.pdf) et le code Python, directement compilable depuis Google Colab, est accessible [là](https://github.com/ARKEnsae/JobDomainPrediction_NLP/blob/main/JobDomainPrediction_NLP.ipynb)

