#Programmation non bloquante

Utilisation de l'AsyncTask

1. Crée dans MainActivity une classe MoveLift qui étend AsyncTask.
2. Supprime la fonction waitForIt et fais en sorte que ce soit MoveLift qui se charge de faire attendre l'utilisateur de l'ascenseur, et après 3 secondes de changer d'étage.
3. Modifie l'endroit où tu indiques à l'application que l'ascenseur s'est arrêté (isLiftMoving)

Critéres de validation

- Le fichier strings.xml contient tous les textes qui sont affichés dans la UI
- L'ascenseur doit prendre 3 secondes pour aller à chaque étage. Le compteur d’étage doit être mis à jour après chaque étage parcouru.
- Il doit être possible de réutiliser l’ascenseur une fois qu’il a atteint un étage, que ce soit pour monter ou descendre.
- Un AsyncTask doit obligatoirement être utilisé et le système qui fait patienter l’ascenseur doit être dans le doInBackground
