---- PROJET DEV MOBILE ----

Mini jeu calcul mentale , 2 langues (FR + une autre)

Android 9.0

3 notes :

Une sur la partie visuel : User expérience

Une sur la partie java : fonctionnement général de l'appli

Une partie BDD : init de la base , sauvegarde , récupération de données.

Une activité menu principal :

2 boutons minimums, un bouton Vers l'écran de jeu , un bouton sur une page highscore Une activité jeu :

Une toolbar avec dedans le score et le nombre de vie restante

TextView : Un calcul sera généré dans une textView

A chaque bonne réponse score +1 
A chaque mauvaise réponse vie -1

Si plus de vie, on ouvre une activité d'enregistrement (Score via Intent)

Activité d'enregistrement :

Un champs de saisie de texte , et un bouton enregistrer (lors d'un appui sur enregistrer on vient save dans une BDD au minimum le score et le pseudo)

Activité high score:

Au chargement on affiche les infos du meilleur ( On vient select uniquement le meilleur score)

Activité a propos :

Les 2 noms du binômes, Feature en plus.

Contact : jerome.gerard02@outlook.fr
