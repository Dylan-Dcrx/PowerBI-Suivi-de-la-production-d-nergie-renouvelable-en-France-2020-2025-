# 📊 Suivi de la production d’énergie renouvelable en France (2020–2025)

Projet Power BI réalisé dans le cadre d’une étude pour Enedis, visant à analyser l’évolution du parc de production d’énergie renouvelable raccordé au réseau de distribution.  
L’objectif est de fournir un tableau de bord interactif permettant d’anticiper l’évolution du mix énergétique, d’identifier les zones à fort potentiel et d’accompagner les décisions d’investissement.

---

## 🎯 Objectifs du projet
- Centraliser et nettoyer des données issues de plusieurs sources (Enedis, Météo France, ensoleillement, référentiels ER).  
- Construire un modèle de données robuste et réutilisable.  
- Créer des KPI métiers (puissance installée, stockage, rendement théorique…).  
- Concevoir un tableau de bord interactif pour le pilotage énergétique.  
- Mettre en place des pages dédiées :
  - Suivi global de la production  
  - Détails par région (drill-through)  
  - Analyse climatique & performance photovoltaïque  

---

## 🗂️ Contenu du dépôt
- **/raw_data** : données brutes (Enedis, Météo France, ensoleillement, référentiel ER)  
- **/report** : fichier Power BI (.pbix)  
- **/documentation** :
  - screenshots des pages  
  - documentation complète (nettoyage, transformations, modèle, KPI, analyses)  
- **README.md** : présentation du projet  

---

## 🧱 Modèle de données
- Table de faits : Production énergie renouvelable  
- Dimensions :
  - Température moyenne France 2020–2025  
  - Temps d’ensoleillement 2024  
  - Type d’énergie renouvelable  
  - Calendrier (table DAX)  
- Relations optimisées, dont une relation bidirectionnelle pour l’analyse climatique.

---

## 📐 KPI & mesures DAX
- % installations avec stockage  
- Puissance installée photovoltaïque (2024)  
- Rendement théorique (MW/J)  
- Nombre total d’installations  
- Puissance totale (MW)  
- Puissance moyenne par région  
- Top 3 par type de production  

---

## 📸 Aperçu du dashboard
Screenshots disponibles dans le dossier `/documentation`.

Pages du rapport :
1. Suivi de production d’énergie renouvelable  
2. Détails par région (drill-through)  
3. Analyse climatique & performance photovoltaïque  
4. Commentaires  

---

## 📝 Documentation
La documentation complète du projet est disponible dans le dossier `/documentation`.

---

## 👤 Auteur
**Dylan Ducroux**  
Data Analyst – Power BI & Performance  

