# 🎬 [Ciné-Reco : Votre prochain coup de cœur cinématographique](https://monprojet2-i5pnumsqnmcnnkkbszaqiq.streamlit.app/)

Bienvenue sur **Ciné-Reco**, une application intelligente de recommandation de films. Ce projet utilise le Machine Learning pour analyser vos goûts et vous proposer des films pertinents parmi une base de données optimisée.

---

## 🚀 Fonctionnalités
* **Expérience Immersive** : Une interface soignée avec une vidéo d'introduction interactive.
* **Moteur de Recommandation** : Algorithme basé sur la similarité pour des suggestions précises.
* **Contenu Multimédia** : Visionnage des bandes-annonces et affichage des biographies des acteurs en temps réel.
* **Design Personnalisé** : Interface stylisée en CSS pour une ambiance "Salle de Cinéma".

---

## 🧠 Le Moteur de Recommandation

L'application utilise l'algorithme des **k-plus proches voisins (k-Nearest Neighbors)**. 

Notre moteur de recommandation analyse vos goûts et vous propose des films similaires. Plus vous aimez un style ou un acteur, plus les suggestions seront pertinentes.
---

## 🛠️ Stack Technique
* **Langage** : Python 3.x
* **Interface** : [Streamlit](https://streamlit.io/)
* **Machine Learning** : Scikit-Learn (NearestNeighbors)
* **Data** : Pandas & Numpy
* **Mise en page** : HTML5 / CSS3 injection

---

## 📦 Installation & Test Local

1. **Cloner le projet**
  
    git clone https://github.com/edouardhurteau-lab/Mon_projet2.git
    cd Mon_projet2

2. **Installer les bibliothèques nécessaires**

    pip install -r requirements.txt

3. **Lancer l'application**

    streamlit run test2.py

## 📂 Structure des fichiers
test2.py : Le code source de l'application.
requirements.txt : Liste des dépendances pour le déploiement Cloud.
df_ML.csv : Données vectorisées utilisées par l'algorithme.
df_FINAL_movie.csv & df_FINAL_intervenant.csv : Bases de données descriptives.


## 👤 Auteur
Edouard Hurteau, Projet réalisé dans le cadre de ma formation en Data Analyse.
En collaboration avec 2D3creuse
---