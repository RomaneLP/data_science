
# Projet

[Importance d'un joueur sur l'issue d'un match de basket](https://github.com/RomaneLP/data_science)

# Étudiants

- Romane LEPOTIER: romane.lepotier@ensae.fr
- Arthur LEROUDIER: arthur.leroudier@ensae.fr

# Examinateur

Daniel Marin: dmarin@open-dc.com

# Commentaires Examinateur

| Thème            | Points positifs                                                                                                               | Points à améliorer                                                                                                                                                                                                                                                                                                                |
|------------------|-------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Reproductibilité | - Modules utilisés détaillés dans un fichier<br/>- Code tourne                                                                | - le fichier de modules devrait être nommé `requirements.txt`                                                                                                                                                                                                                                                                     |
| Qualité du code  | - code concis et "pythonesque"                                                                                                | - fichier `declarations.py` vide<br/>- Peu de commentaires dans le code<br/>- Boucles sur les rows de dataframes (méthode `iterrows` de `pandas`) peu efficace en général<br/>- La génération des 20 appels à l'url aurait pu être automatisée plutôt que de lancer 20 fois manuellement le script en changeant les paramètres... |
| Activité GitHub  | - Commits bien distribués entre les membres de l'équipe                                                                       | - Commentaires de commit pourraient être plus explicites                                                                                                                                                                                                                                                                          |
| Jeu de données   | - Données scrappées de [Basketball Reference](https://www.basketball-reference.com/tools/share.fcgi?id=WumlT)                 | - un peu d'open data pour compléter l'analyse aurait été bienvenue                                                                                                                                                                                                                                                                |
| Nettoyage        | - Manipulation / nettoyage de chaines de caractères                                                                           |                                                                                                                                                                                                                                                                                                                                   |
| Visualisation    | - `matplotlib`                                                                                                                | - Des sorties autres que des histogrammes auraient été bienvenues                                                                                                                                                                                                                                                                 |
| Modélisation     | - Utilisation de trois algos à comparer: régression, arbre de décision et forêt aléatoire<br/>- Utilisation de `scikit-learn` |                                                                                                                                                                                                                                                                                                                                   |
| Notebook         | - Bonne qualité de rédaction                                                                                                  | - Utilisation abusive des formats de titres<br/>- Notebook relativement léger                                                                                                                                                                                                                                                     |
