# my_new_project
building IA cours project
SmartWaste – Détection intelligente des déchets

 ## Résumé
SmartWaste est un projet d’intelligence artificielle qui utilise la vision par ordinateur pour identifier et classer automatiquement les déchets à partir d’images.  
L’objectif principal est d’aider les citoyens et les municipalités à améliorer le tri sélectif et réduire la pollution.

## Objectifs
- Détection automatique des déchets à partir d’une photo 
- Classification en catégories : plastique, papier, métal, verre, autres
- Proposition de la bonne poubelle pour chaque objet
- Sensibilisation des citoyens via une application simple et intuitive

##  Technologies utilisées
- Python  
- TensorFlow / Keras (réseaux de neurones convolutifs CNN)  
- Transfer Learning avec MobileNetV2  
- Streamlit (pour l’interface utilisateur interactive)  

## Données
- Dataset : [TACO (Trash Annotations in Context)](http://tacodataset.org/)  
- Images de déchets annotées dans des environnements réels  
- Prétraitement : redimensionnement, normalisation, augmentation de données  

## Méthodologie
1. Préparation et nettoyage des données  
2. Entraînement d’un modèle CNN avec transfer learning (MobileNetV2)  
3. Évaluation sur un jeu de test (accuracy, matrice de confusion)  
4. Déploiement via une interface Streamlit (l’utilisateur charge une image et obtient la catégorie du déchet en temps réel)  

##  Résultats
- Précision du modèle : ~85% sur le jeu de test  
- Capacité à distinguer efficacement les principales catégories de déchets  
- Démonstration interactive via une app Streamlit  

##  Défis rencontrés
- Variabilité des images (lumière, arrière-plans complexes, objets sales)  
- Nécessité de beaucoup de données annotées  
- Optimisation pour un usage sur smartphone (limites matérielles)  

##  Perspectives
- Améliorer la précision avec plus de données et d’architectures avancées (EfficientNet, ResNet)  
- Détection en temps réel via caméras de surveillance des poubelles publiques  
- Système de récompenses/gamification pour encourager les citoyens à trier leurs déchets  

##  Remerciements
- Dataset : [TACO](http://tacodataset.org/)  
- Frameworks : TensorFlow, Keras, Streamlit  
- Inspiration : projets d’IA appliqués à l’écologie et au développement durable  
