# **Documentation Utilisateur : Régression par Gradient Boosting**

## **Introduction**

La Régression par Gradient Boosting est une fonctionnalité qui permet de prédire une valeur continue (comme un prix, une température, etc.) à partir de données. Cette documentation vous guide pas à pas pour utiliser cette fonctionnalité.


### **Comment utiliser la fonctionnalité**

***Étape 1 : Importer des données***
1.Cliquez sur le bouton **"Importer des donnée"**.
2.Sélectionnez un fichier CSV ou Excel contenant vos données. 

- Le fichier doit avoir des colonnes numériques (par exemple, X et Y).

3.Les colonnes du fichier seront automatiquement chargées dans les menus déroulants.

***Étape 2 : Sélectionner les variables***

**1.Variable indépendante (X) :** Sélectionnez la colonne à utiliser comme variable explicative (par exemple, X).
**2.Variable dépendante (Y) :** Sélectionnez la colonne à prédire (par exemple, Y).

***Étape 3 : Configurer le modèle***

**1.Nombre d'arbres :** Entrez le nombre d'arbres à utiliser (par défaut : 100).

**2.Taux d'apprentissage :** Entrez la vitesse à laquelle le modèle apprend (par défaut : 0.1).

**3.Profondeur maximale :** Entrez la profondeur maximale des arbres (par défaut : 3).

***Étape 4 : Calculer la régression***

1.Cliquez sur le bouton **"Calculer la régression".**

2.Le modèle sera entraîné, et les résultats seront affichés :

- Un graphique montrant les valeurs observées (Y) vs les valeurs prédites.
- Les métriques de performance (MSE et R²) sous le graphique.

#### Exemple de cas d'utilisation:

1. ***Contexte***

   Vous êtes responsable marketing dans une entreprise, et vous souhaitez prédire les ventes futures en fonction des dépenses publicitaires. Vous avez des données historiques sur les dépenses publicitaires (X) et les ventes correspondantes (Y). Vous voulez utiliser la Régression par Gradient Boosting pour créer un modèle prédictif.

##### FAQ

**Que faire si les données ne sont pas chargées ?**
Vérifiez que le fichier est au format CSV ou Excel.
Assurez-vous que les colonnes sont numériques.

**Comment améliorer les performances du modèle ?**
Augmentez le nombre d'arbres (n_estimators).
Ajustez le taux d'apprentissage (learning_rate).
Expérimentez avec la profondeur maximale (max_depth).

 **Pourquoi le graphique n'affiche-t-il rien ?**
Vérifiez que les variables X et Y sont correctement sélectionnées.
Assurez-vous que les données sont valides (pas de valeurs manquantes ou aberrantes).

###### **Conclusion**

La fonctionnalité de Régression par Gradient Boosting est un outil puissant pour prédire des valeurs continues. En suivant ce guide, vous pouvez facilement entraîner un modèle, visualiser les résultats et interpréter les métriques de performance.

**Besoin d'aide ?**
Si vous rencontrez des problèmes ou avez des questions, contactez notre équipe de support à support@votreapplication.com.

**Références**
Documentation scikit-learn (GradientBoostingRegressor)
Documentation Matplotlib