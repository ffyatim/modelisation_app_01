# P7-Scoring - Implementez & Deployez un scoring modèle

1. Objectif du projet:
(voir aussi https://openclassrooms.com/fr/paths/164/projects/632/assignment)

L’entreprise souhaite:
- mettre en œuvre un outil de “scoring crédit” pour calculer la probabilité qu’un client rembourse son crédit, puis classifie la demande en crédit accordé ou refusé. 
- développer un dashboard interactif pour que les chargés de relation client puissent à la fois expliquer de façon la plus transparente possible les décisions d’octroi de crédit. 
- Spécifications du dashboard:
  Permettre de visualiser le score et l’interprétation de ce score pour chaque client de façon intelligible pour une personne non experte en data science.
  Permettre de visualiser des informations descriptives relatives à un client (via un système de filtre).
  Permettre de comparer les informations descriptives relatives à un client à l’ensemble des clients ou à un groupe de clients similaires 

2. Code: modelisation_app_01.ipynb (prétraitement à partir d'un noyau Kaggle existant)
Cette partie du code concerne l'analyse exploratoire des données (EDA).
Deux autres parties (dashboard - streamlit) et (api - Flask) sont presentées dans des repertoires indépendants.

3. Données en entrée: 
- Fichiers csv fournis a l'addresse https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Impl%C3%A9menter+un+mod%C3%A8le+de+scoring/Projet+Mise+en+prod+-+home-credit-default-risk.zip 
- Une copie zippée de l'ensemble des fichiers existe dans ce repertoire aussi.

4. Donnéesn en sortie:
- application_sample.csv : Fichier nettoyé et pre-traité (EAD)
- X_train_sample.csv: Fichier csv d'entrainement du modele
- XGB_clf_model_f.pkl : Le XGBoostClassifier modele
