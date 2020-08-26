# Initiation au langage C\#

Durant cette initiation, tu apprendras à utiliser des méthodes du framework .NET pour récupérer une *saisie utilisateur*. Tu vas aussi concevoir un algorithme qui permettra de jouer avec l'ordinateur.

## Préparation

Installe Visual Studio 2019 si ce n'est pas déjà fait. L'installation peut être longue alors il vaut mieux la commencer maintenant. 

## Le plus ou moins

Le principe de cette initiation est de réaliser un jeu du plus ou moins. Le principe de ce jeu est on ne peut plus simple. Considérons un joueur A et un joueur B:

* A choisit un nombre entre 1 et 100
* B lui propose un nombre entre 1 et 100
  * Si le nombre qu'a choisi B est supérieur au nombre qu'a choisi A, A doit dire "Moins"
  * Si le nombre qu'a choisi B est inférieur au nombre qu'a choisi A, A doit dire "Plus"
  * Si les nombres qu'ont choisi B et A sont égaux, alors le jeu est terminé
  * Autrement le jeu continue jusqu'à ce que B ait trouvé le nombre qu'a choisi A

## Un code à trous

Tu partiras d'un code pré-existant dans lequel il ne faudra rien modifier à part les zones où il est permis de le faire. Ainsi, dans le fichier [Program.cs](https://github.com/WildCodeSchool/InitiationCSharp/blob/master/Program.cs) tu devras écrire le *corps de la méthode* `PrintComputerHint` ainsi qu'un morceau du *corps de la méthode* `PlayTurn`.

## Tirer le dépôt

Afin de cloner le dépôt pour pouvoir commencer à travailler, exécute dans un terminal la commande `git clone https://github.com/WildCodeSchool/InitiationCSharp`

## Fichier sln

Ouvre le fichier sln avec Visual Studio et tu pourras commencer à coder. Un triangle vert (bouton Play) compilera le code et le lancera.
