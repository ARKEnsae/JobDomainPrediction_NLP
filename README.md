# NLP for Job Domain Prediction  <img src="Rapport/img/LOGO-ENSAE-avatar.png" align="right" alt=""  width="100"/>

Projet de fin de semestre pour le cours de Machine Learning for Natural Language Processing (ENSAE 3A) @antuki @AQLT

En travaillant sur des données de Pôle Emploi et Onisep, nous avons utilisé des modèles de NLP pour prévoir le domaine d'un emploi (grand domaine de l'arborescence ROME) en utilisant que sa description. 
Pour cela nous avons implémenté plusieurs modèles :

- à partir d'un SVM à partir d'une représentation vectorielle des phrases construite grâce à un modèle [pré-entrainé word2vec](https://fauconnier.github.io)

- à partir de *Long short-term memory* (LSTM), qui sont des réseaux de neurones récurrents, en utilisant ou non des représentations vectorielles des mots déjà connue.

- à partir du modèle de langage pré-entrainé CamemBERT, qui utilise une architecture bidirectionnelle de *transformer*, qui peut être adapté pour la classification de séquences (`BertForSequenceClassification`).

Le rapport est disponible [ici](https://arkensae.github.io/JobDomainPrediction_NLP/Rapport/Rapport.pdf) et le code Python, directement compilable depuis Google Colab, est accessible [là](https://github.com/ARKEnsae/JobDomainPrediction_NLP/blob/main/Prévision_catégorie_métier_ROME.ipynb)

