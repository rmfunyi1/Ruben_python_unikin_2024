
## **Titre :** Analyse des Données Géospatiales de Columbus, Ohio

### **Description :**
Ce notebook Jupyter présente une analyse géospatiale des taux de criminalité dans la ville de Columbus, Ohio, en utilisant des bibliothèques Python telles que GeoPandas, Matplotlib, et d'autres outils associés. L'objectif est de visualiser et d'analyser la distribution des crimes dans différents quartiers de la ville, en utilisant des techniques de classification et de visualisation de données géospatiales.

### **Contenu :**
Le notebook contient les sections suivantes :

1. **Importation des Bibliothèques** :
   - Importation des bibliothèques nécessaires pour l'analyse géospatiale, notamment GeoPandas, Matplotlib, et PySAL.

2. **Chargement des Données** :
   - Chargement d'un shapefile représentant les quartiers de Columbus, Ohio, et affichage des premières lignes des données pour une inspection initiale.

3. **Analyse de la Distribution de la Criminalité** :
   - Création d'un histogramme pour visualiser la distribution des taux de criminalité (CRIME) à travers les différents quartiers.
   - Affichage de la répartition des taux de criminalité sur une carte thématique de Columbus.

4. **Visualisation Spatiale des Données** :
   - Visualisation des taux de criminalité sur une carte en utilisant différentes techniques de classification, telles que les quantiles, les intervalles égaux, et les ruptures naturelles.

5. **Étude de Cas Additionnelle** :
   - Analyse fictive de la distribution des taux de criminalité à l'échelle des États-Unis, en utilisant des données simulées pour illustrer les capacités de GeoPandas.

### **Dépendances :**
Le notebook nécessite l'installation des bibliothèques suivantes :
- `geopandas`
- `matplotlib`
- `libpysal`
- `mapclassify`
- `numpy`

Les installations peuvent être effectuées via pip :

```bash
pip install -r requirements.txt
```

### **Instructions d'Utilisation :**
1. **Téléchargez et ouvrez le notebook** :
   - Assurez-vous que vous avez installé toutes les dépendances requises à partir du requirements.txt.
   - Ouvrez le fichier `.ipynb` dans un environnement Jupyter (comme Jupyter Notebook ou JupyterLab).

2. **Exécutez les cellules dans l'ordre** :
   - Suivez l'ordre des cellules dans le notebook pour effectuer l'analyse. Chaque cellule de code est accompagnée de commentaires expliquant son rôle.

3. **Analysez les Résultats** :
   - Les visualisations générées vous donneront une compréhension claire de la distribution spatiale de la criminalité à Columbus, Ohio.

