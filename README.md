# -A-Study-on-buildig-a-Paraphrasing-Model-using-deep-learning-techniques
Ce projet consiste en la conception et l'implémentation d'un modèle de paraphrase automatique utilisant des techniques de deep learning. Il inclut une interface utilisateur web développée avec Flask pour permettre une interaction facile avec le modèle.

## Objectifs
- Comparer les performances des modèles Parrot, T5 et Pegasus pour la tâche de paraphrase.

- Développer une interface utilisateur intuitive pour interagir avec le modèle retenu.

- Évaluer la qualité des paraphrases générées à l'aide de métriques telles que BLEU et ROUGE.

## Modèles utilisés
- Parrot : Modèle encodeur-décodeur basé sur T5.

- T5 (Text-to-Text Transfer Transformer) : Modèle Transformer polyvalent fine-tuné pour la paraphrase.

- Pegasus : Modèle conçu pour le résumé de texte, adaptable à la paraphrase.

## Résultats
Le modèle T5 a obtenu les meilleurs scores sur le jeu de données CNN/Daily Mail :

Modèle	BLEU-1	BLEU-2	ROUGE-L
Parrot	0.82	0.67	0.75
T5	0.91	0.79	0.86
Pegasus	0.85	0.72	0.80  

## Technologies utilisées
- Python

- Flask (interface web)

- Hugging Face Transformers

- Google Colab

- NumPy

- Datasets (Hugging Face)

## Exemple de résultat
### Texte original :
"Five Americans who were monitored for three weeks at an Omaha, Nebraska, hospital after being exposed to Ebola in West Africa have been released..."

### Paraphrase générée (T5) :
"Five Americans monitored for three weeks after being exposed to Ebola. One has been discharged but hasn’t left the area, spokesman writes. They are clinicians for Partners in Health, a Boston-based aid group."

## Rapport complet
Le rapport détaillé du projet est disponible ici : PFE 2023 Report _ Paraphrasing ML.pdf

## Licence
Ce projet est ouvert à des fins éducatives et de recherche.
