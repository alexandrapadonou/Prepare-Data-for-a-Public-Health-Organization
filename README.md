# Prepare Data for a Public Health Organization
![image](https://github.com/user-attachments/assets/1e2a6842-5100-4809-83db-0980f4cebfd4)

In this project, I will develop exploratory analysis skills while focusing on data cleaning and multivariate analysis.

Ce projet utilise les bibliothèques Python suivantes :

- **Pandas** : pour le traitement et l'analyse des données.
- **NumPy** : pour les calculs numériques.
- **Matplotlib** et **Seaborn** : pour les visualisations.
- **Scikit-learn** : pour les analyses statistiques et d'apprentissage machine.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.x-green.svg)
![NumPy](https://img.shields.io/badge/NumPy-1.x-orange.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-red.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-yellow.svg)
![Missingno](https://img.shields.io/badge/Missingno-0.5.2-purple.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.x-lightblue.svg)


---

# Analyse des Données Open Food Facts

Ce projet vise à nettoyer, analyser et visualiser les données issues de la base Open Food Facts afin d'assister un organisme de santé publique dans ses prises de décision.
Le jeu de données Open Food Facts utilisé dans ce projet est disponible via les liens suivants :

- **Site officiel** : [Open Food Facts](https://world.openfoodfacts.org/)
- **Téléchargement direct** : [Données en format CSV](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-scientist/P2/fr.openfoodfacts.org.products.csv.zip)
- **Définition des variables** : [Liste des champs de données](https://world.openfoodfacts.org/data/data-fields.txt)


## Objectifs du Projet

1. **Traitement du Jeu de Données**
   - Identifier les variables pertinentes pour les traitements futurs.
   - Nettoyer les données :
     - Détection et traitement des valeurs manquantes avec au moins trois méthodes adaptées.
     - Identification et gestion des valeurs aberrantes.
   - Automatisation des processus de nettoyage pour garantir la reproductibilité, même en cas de modifications légères des données (par ex. ajout de nouvelles entrées).

2. **Visualisations et Analyse Exploratoire**
   - Créer des visualisations pour mieux comprendre les données.
   - Réaliser une analyse univariée pour chaque variable intéressante (histogrammes, boxplots, diagrammes circulaires, etc.).
   - Adapter les visualisations pour un public néophyte avec des choix clairs de couleurs, de textes, et de graphiques variés.

3. **Analyse Multivariée et Sélection de Variables**
   - Effectuer une analyse multivariée pour sélectionner ou créer de nouvelles variables pertinentes.
   - Vérifier la significativité des résultats à l'aide de tests statistiques appropriés.

4. **Rapport d'Exploration et Conclusion**
   - Rédiger un rapport synthétisant les analyses effectuées et les résultats obtenus.
   - Évaluer la faisabilité de l'application demandée en fonction des données.

5. **Respect des Principes du RGPD**
   - Expliquer en quoi le projet respecte les cinq grands principes du RGPD (Règlement Général sur la Protection des Données).
   - Fournir un document destiné à Santé Publique France pour publication sur le site Open Food Facts, répondant aux préoccupations concernant le respect du RGPD.

---

## Détails des Étapes

### 1. Traitement du Jeu de Données

#### Sélection des Variables Pertinentes
- Analyse préliminaire pour déterminer les variables nécessaires à l'étude.

#### Gestion des Valeurs Aberrantes
- Analyse métier  couplée a l'analyse des distributions via des graphiques comme les boxplots pour détecter les valeurs extrêmes.

- #### Gestion des Valeurs Manquantes
- **Méthodes utilisées :**
  - Remplissage par la moyenne/médiane pour les données quantitatives.
  - Remplissage orienté métier
  - Remplissage grâce à l'itérative imputer et le KNN
    

### 2. Visualisations et Analyse Exploratoire
- Graphiques variés pour illustrer les tendances et distributions :
  - Histogrammes pour les distributions.
  - Nuages de points pour les corrélations.
  - Boxplots pour détecter les anomalies.
- Lisibilité garantie pour un public non-expert (choix de couleurs harmonieuses, annotations claires).

### 3. Analyse Multivariée et Sélection de Variables
- Méthodes utilisées :
  - Analyse en composantes principales (ACP).
  - Tests d'hypothèses pour valider les relations entre variables.


---

## Résultats Attendues
- Une base de données propre et analysable.
- Visualisations claires et pertinentes.
- Documentation expliquant chaque étape pour un public non technique.

---
