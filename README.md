# Devoir 05 : Chaussures
## CONSIGNE :
Lisez `avec attention` et faites les points suivants avec précision et dans cet ordre :
- Créez une classe java permettant de créer un objet **chaussure**. Créez cette classe dans le bon package.
- Faites en sorte qu’une **chaussure** soit caractérisée par une marque, un prix, s'il s'agit d'une chaussure gauche ou droite et, dernière caractéristique d'une chaussure, ses points d’usure *(un nombre entier de 0 à 100, un 0 indiquant aucune usure et donc totalement neuve et 100 une chaussure totalement usée/détruite)*.
- Donnez-lui les getters/setters utiles sachant qu'on veut à tout moment pouvoir interoger une chaussure pour obtenir ses caractéristiques propres, mais que seule l'usure de la chaussure pourra être modifiée après création.
- Renforcez cet état de fait dans la déclaration des attributs concernés.
- Faites en sorte que l'affichage d'une chaussure affiche les informations suivantes de cette manière : "La chaussure gauche 'Nike' à 129.90 Frs usée à 5%".
- Donnez-lui ensuite le savoir-faire de `marcher`. Si le taux d'usure n'est pas encore de 100, cette action affichera le toString() de la chaussure suivi de " - Marche" et lui ajoutera 1 point d’usure.  Si le taux d'usure est de 100, elle devra afficher "Chaussure droite 'Adidas' à 89.90 Frs inutilisable !".
- Donnez-lui également la capacité de se `nettoyer`, ce qui lui enlèvera 10 points d’usure (sans toutefois passer en dessous de zéro) puis affichera le toString() de la chaussure suivi de " - Nettoyée !".
- Dans le main() du programme :
  - Créez quelques chaussures différentes avec des caractéristiques différentes.
  - Affichez vos chaussures.
  - Faites-les marcher et nettoyez-les afin de tester les fonctionnalités.
  - Créez une chaussure droite 'Nike EMF' à 123.45 Frs. Dans une boucle faites-là marcher 110x. Nettoyez-la 1x. Faites-là marcher 2x.


## RESTITUTION :
1. Rendre ce devoir normalement par `push` GitHub
2. Mettez le code de vos 2 classes Java en couleur dans un document Word que vous rendrez comme devoir sur Teams.
