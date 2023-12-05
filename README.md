Implémenter la fonction 'seg\_couleur' définie par la syntaxe suivante permettant de segmenter une image couleur RGB:

       $S$ =  color\_seg(method, $f$, $T$, paramètres)

où 'method' est soit 'euclidean' ou 'mahalanobis', $f$ est l'image couleur RGB à segmenter, et $T$ représente le seuil de segmentation. Les paramètres d'entrée représentent la moyenne $m$ ou la matrice de covariance $C$ selon la distance choisi 'euclidean' ou 'mahalanobis', respectivement. La sortie $S$, est une image binaire ayant la même taille que l'image originale $f$ contenant le résultat de la segmentation, par exemple les 1s et les 0s représentent l'objet et l'arrière-plan, respectivement.
