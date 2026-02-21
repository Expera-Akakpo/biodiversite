# 🍃 Analyse de la Biodiversité - Grand Est 2025

Ce projet propose une exploration interactive et analytique des données de biodiversité (faune, flore, milieux naturels) de la région Grand Est.  
Initialement conçu dans l'esprit du concours DataGrandEst 2025, ce dashboard met en lumière les tendances écologiques tout en traitant de manière critique les biais d'observation.

---

## Lien du Dashboard
https://biodiversiteacue.streamlit.app

---

## Fonctionnalités Clés

### Visualisation Géographique
- Cartes de chaleur (Heatmaps)  
- Cartes choroplèthes par commune/département  
- Intégration via **Folium**

### Analyse Temporelle
- Évolution des observations (2012–2024)  
- Lissage statistique **LOESS** pour filtrer le bruit des données  

### Storytelling Data
- Identification de l’effet *confinement* de 2020  
- Analyse de l’effort d’observation  
  - Distinction entre présence réelle d’une espèce  
  - Densité des observateurs  

### Interface Intuitive
- Menu latéral de navigation  
- Vues géographiques  
- Graphiques de saisonnalité  
- Recommandations stratégiques  

---

## Technologies Utilisées

- **Langage :** Python 3.x  
- **Framework Web :** Streamlit  
- **Analyse de données :** Pandas, GeoPandas, Scipy, Statsmodels  
- **Visualisation :** Plotly, Matplotlib, Seaborn, Folium  
- **Déploiement :** Streamlit Cloud / GitHub  

---

## Structure du Répertoire

```

biodiversite/
│
├── app.py              # Application Streamlit (logique + visualisations)
├── requirements.txt    # Dépendances Python
├── data/               # Fichiers CSV et GeoJSON
├── ...

````

## Installation et Utilisation Locale

### Cloner le projet

```bash
git clone https://github.com/Expera-Akakpo/biodiversite.git
cd biodiversite
````

### Installer les dépendances

```bash
pip install -r requirements.txt
```

### Lancer l'application

```bash
streamlit run app.py
```

## 📝 Auteur
Expera Akakpo
Passionné par la Data Science et le Storytelling.

Projet réalisé dans le cadre d'une participation libre à la 3ème édition du concours de datavisualisation organisé par DataGrandEst.
