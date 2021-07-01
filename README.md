# Que-la-taille-qui-compte
Une société qui revient vers nous pour améliorer l'algorithme que nous lui avons déjà fourni.
## Modèles
le model1 est un modèle sans la couche de dropout et sans data augmentation: on remarque sur le graphe des loss un overfitting.
le modèle model est un modèle sans dropout mais avec data augmentation et on remarque qu'il n' ya pas d'overfitting.
les deux modèles model1 et model sont dans le fichier model_cifar.Rmd

dans le fichier modelCnn_cifar.R, le modèle model est entrainé sans data augmentation mais avec une couche de dropout.
Trois captures d'écran pour visualiser chacun des trois cas. 
