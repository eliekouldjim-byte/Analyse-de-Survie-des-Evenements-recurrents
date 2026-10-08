# Analyse de survie des évènements recurrents

Ce projet s’intéresse à l’analyse de survie des événements récurrents dans le cadre des études longitudinales.

Il met particulièrement l’accent sur :
- les modèles adaptés aux événements répétés chez un même individu ;
- les limites du modèle de Cox classique, notamment l’ignorance de la corrélation intra-sujet ;
- la comparaison de modèles étendus (Andersen–Gill, PWP, marginal, fragilité) ;
- la nécessité d’un choix de modèle tenant compte de la dépendance des événements et du contexte
biologique

##  Contexte
Projet réalisé dans le cadre du cours d'analyse de Survie, en 2025.

**Objectif** : Il met particulièrement l’accent sur :

- les modèles adaptés aux événements répétés chez un même individu ;
- les limites du modèle de Cox classique, notamment l’ignorance de la corrélation intra-sujet ;
- la comparaison de modèles étendus (Andersen–Gill, PWP, marginal, fragilité) ;
- la nécessité d’un choix de modèle tenant compte de la dépendance des événements et du contexte
biologique.

##  Ce que fait le projet
- Etude de simulation pour comparer les modèles (cox standard, Andersen–Gill, PWP, marginal, fragilité)
- Application aux données réélles : Données contient des événements récurrents d’infections chez des patients atteints de granulomatose
chronique (CGD)

##  Outils
- R
- Survival, Coxmodel, PWP, marginal,
- Rmarkdown
