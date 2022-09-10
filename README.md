# Wine-Quality-with-Machine-Learning
Ce projet consiste à mettre sur pied un modèle de machine learning permettant de déterminer la qualité du Vin en fonction de ses caractéristiques.
#  Description du Dataset
Le dataset dont nous disposons est constitué de 1599 échantillons de vin rouge. Chacun des échantillons dispose de 12 caractéristiques ou variables qui sont:fixed acidity,  volatile acidity,  citric acid,  residual sugar,  chlorides, free sulfur dioxide, total sulfur dioxide, density,  pH, sulphates,  alcohol et  quality (score between 0 and 10).
# Librairies Python Utilisées
Pandas, Numpy, Seaborn, matplotlib et sklearn.
# Prise en main du Dataset
Nous avons donc effectué une lecture de notre dataset dans l’espace de travail, affiché les 5 premières lignes du dataset, vérifié s' il n’y a pas des valeurs manquantes dans notre dataset et consulté la forme de l’ensemble de notre dataset.
# Analyse et Visualisation du Dataset
Nous avons donc ressorti le nombre de valeurs de chaque variable, calculer la moyenne des valeurs de chaque variable, trouver la valeur minimale et maximale de chacune de ces variables. En ce qui concerne la variable dépendante ‘quality’ qui est la qualité du vin dépendant des autres variables, nous avons compté le nombre d'instances de chacune de ses valeurs.Nous avons ensuite observé la relation de variation qui pourrait avoir entre cette qualité et d’autres caractéristiques tels que volatile acidity et citric acid. Ensuite nous avons calculé la corrélation entre  les différentes variables et nous avons affiché la matrice de corrélation.
# Prétraitement
Nous avons ensuite effectué un prétraitement qui a consisté à séparer la variable dépendante des autres variables et la binarisation de cette dernière tels que, pour les valeurs de qualité supérieures à 7, la qualité vaut 1(bon vin), sinon la qualité vaut 0(mauvais vin). Nous avons ensuite divisé nos données en données d'entraînement (70%) et données test(20%).
# Entrainement et Evaluation
Nous avons entraîné notre modèle avec l’algorithme de Random Forest et nous l’avons évalué sur les données test. On a obtenu une précision de 93.7%.
# Evaluation avec les algorithmes Random Forest et SVM
Le premier resultat obtenu avec l'algorithme Random Forest nous donne une précision de 93.7% tandis avec l'entrainement avec l'algorithme SVM nous donne une précision de 88.4%. Donc on peut conclure que l'algorithme Random Forest a une meilleure performance que SVM dans ce cas de classification.

