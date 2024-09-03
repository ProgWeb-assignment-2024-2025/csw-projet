# Projet : Conception de site Web
## Objectif du projet
Le but de ce projet est de concevoir et développer un jeu interactif basé sur le concept de "Jeu dont vous êtes le Héros". Le joueur progresse dans une histoire en fonction de ses choix, et rencontre diverses épreuves tout au long du jeu. Ce projet vous permettra de mettre en pratique vos compétences en HTML, CSS et JavaScript.

## Spécifications techniques

### Structure de l'histoire :
L'histoire doit être divisée en plusieurs chapitres, chacun présentant un morceau de l'histoire.

À la fin de chaque chapitre, le joueur doit faire un choix parmi plusieurs options pour déterminer la suite de l'histoire.

_Note importante: Lorsque l’on parle de « chapitres », il ne s’agit pas de créer une page HTML par chapitre, le jeu se déroule bien principalement dans une unique page HTML._

### Navigation et Interactivité :
Les choix peuvent être réalisés via des boutons, des zones cliquables sur des images ou tout autres interactions ludiques.
Les transitions entre les sections doivent être fluides et user-friendly.

### Épreuves et défis :
Intégrez au moins un mini-jeu dans votre histoire, qui peut être décliné plusieurs fois avec des variations.

Les épreuves doivent influencer le déroulement de l'histoire en fonction de leur résultat.

### Formulaire initial :
Avant de commencer le jeu, le joueur doit remplir un formulaire avec quelques informations de base (ex. : nom, âge, préférences, etc.).

Ces informations doivent être utilisées pour personnaliser l'expérience de jeu (ex. : intégrer le nom du joueur dans l'histoire).

### Stockage de l'état du jeu :
Utilisez localStorage pour stocker la progression du joueur afin de permettre la reprise du jeu après la fermeture du navigateur.

### Aspect visuel :
Utilisez CSS pour styliser votre jeu de manière cohérente et attrayante.

Les attentes en matière de design ne sont pas excessivement élevées, mais un effort pour rendre le jeu agréable visuellement est attendu.

### Technologies utilisées :
HTML pour la structure du contenu.

CSS pour le style et la mise en page.

JavaScript pour l'interactivité et la logique du jeu.

## Contraintes non techniques

### Commentaires dans le code :
Utilisez des commentaires clairs, concis et pertinents pour expliquer les parties importantes de votre code.

Adoptez le format JSDoc pour documenter vos fonctions, en couvrant la description, les paramètres et les valeurs retournées.
### Méthodologie de travail :
Effectuez des commits réguliers pour documenter l'évolution de votre projet.

Assurez-vous que chaque commit soit accompagné d'un message clair et descriptif.
### Lisibilité du code :
Utilisez des noms de variables et de fonctions explicites.

Suivez une convention de nommage cohérente.

Assurez une indentation et des espacements cohérents.

### Modularité du code :
Découpez votre code en fonctions ayant un but unique et bien défini.

Placez votre code JavaScript dans un ou plusieurs fichiers séparés et évitez d'inclure du JS dans le HTML.

## Validation de l'idée du projet 
Avant de pouvoir démarrer votre projet, vous devez soumettre une proposition d'idée à votre enseignant pour validation. Cette proposition devra être soumise au format Markdown dans un fichier “readme.md” (dans le répertoire _dist_) et doit inclure
* Un résumé de l'histoire que vous souhaitez développer.
* Une idée du mini-jeu que vous allez intégrer, avec une explication de sa mécanique.
* Une explication sur la manière dont vous allez utiliser le formulaire initial et le stockage de l'état du jeu.
