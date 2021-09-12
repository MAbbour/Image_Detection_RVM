# Image_Detection_RVM
** Résumé **
* L'objectif de ce projet est de développer une solution automatique de reconnaissance d'images à implanter dans une RVM (Reverse Vending Machine).
*Détection*
* Pour entrainer des modèles de détection d’objets on a utilisé une API de Tensorflow nommée TFOD (Tensorflow Object Détection).
* On a suivi cette [Documentation](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html) pour la plupart des étapes.
*Classification*
* On a entrainé trois modèles de classification d’images qui sont : XGboost, Random Forest et Logistic regression en utilisant un modèle qui est déjà entrainé pour extraire les caractéristiques et l'utiliser pour entrainer nos modèles qui est dans notre cas VGG16.
