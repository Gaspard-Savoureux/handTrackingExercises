<h1 align="center"> <i><b> ~ handTracking ~ </i></b></h1>

>Je recommande de consulter la documentation officielle de [mediapipe](https://google.github.io/mediapipe/solutions/hands.html) pour plus d'informations.

## Exercises
Les exercices sont déjà complétés et c'est à vous de compléter la librairie que les exercices vont utilisés!
Compléter le fichier [quickHand.py](./exercises/quickHand.py) pour que les fichiers d'exercices fonctionnent.
> **IMPORTANT**: Chaque exercice doit **toujours** être fonctionnel après la modification de [quickHand.py](./exercises/quickHand.py)
> 
> De plus, si votre caméra ne marche pas changez la valeur de VideoCapture.
>```py
>cap = cv2.VideoCapture(0)
>```

>Le numéro précédent les énoncés ci-dessous, indique aussi le numéro de l'exercice.

[1.](exercises/exercise1.py) **(7.5%)**Afficher  les lignes sur la main avec opencv.

[2.](exercises/exercise2.py) **(25%)** Compter le nombre de doigts levés sur une main.

[3.](exercises/exercise3.py) **(25%)** Identifier les mains (droite ou gauche) et ajouter un indicateur textuel pour montrer ceux-ci.
   - Suggestion: Mettre un rectangle autour des mains (avec cv2.rectangle) pour ajouter du texte à une position voulue. (***facultatif et n'affecte pas les points***)
  
[4.](exercises/exercise4.py) **(7.5%)** Ajouter le nombre de doigts présent à côté des doigts vus.

[5.](exercises/exercise5.py) **(20%)** Mesurer la distance entre deux points et afficher une ligne entre ces deux points. Vous devez spécifier la position des points vous-mêmes.
   - **(5%)** [5.1](exercises/exercise5.1.py) entre le pouce et l'index d'une même main.
   - **(10%)** [5.2](exercises/exercise5.2.py) entre les deux index des mains.

### Points Bonus:
(***facultatif***)
1. **(5%)** rendre la taille et la position du texte dynamique selon la position de la main.
2. **(5%)** avoir le bon compte de doigts même si les mains sont inversées.
3. **(5%)** typer les variables, lorsque pertinent. Par exemple, certains paramètres dans les fonctions ne sont pas typés alors qu'il pourrait être très pertinent qu'ils le soient.
