# 📊 Projet Big Data — Pipeline ETL

Master 2 Calcul Scientifique (M2 CS)  
Université de Reims Champagne-Ardenne

Ce projet consiste à concevoir un pipeline ETL complet permettant la collecte, la transformation et l’analyse de données ouvertes afin de produire des indicateurs exploitables.

---

## 👥 Auteurs

- Moulouka Mohamed Daher
- Traoré Yannick Quentin

---

## 🎯 Objectifs

Le projet vise à mettre en place une architecture de données complète :

• Extraction de données depuis des APIs publiques  
• Stockage dans un Data Lake  
• Transformation et nettoyage  
• Chargement dans un Data Warehouse  
• Analyse et visualisation

---

## 🏗️ Architecture du pipeline

Le pipeline suit la **Medallion Architecture** utilisée en industrie Data Engineering.

### 1️⃣ Bronze (Data Lake)
Données brutes collectées depuis les APIs.  
Aucune transformation n’est appliquée.

### 2️⃣ Silver (Data Warehouse brut)
Données nettoyées :
- suppression des valeurs manquantes
- typage des colonnes
- normalisation

### 3️⃣ Gold (Analytics Layer)
Données agrégées prêtes pour l’analyse métier :
- indicateurs
- statistiques
- tableaux analytiques

---

## 📂 Structure du projet
