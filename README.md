# JeuDame

Jeu de dame, projet python Merault Valentin, Garnier Clara.

Nous avons eu comme projet de faire un jeu de dames, pour pouvoir lancer notre jeu il vous suffit de:
-Télécharger pygame en utilisant le tuto disponible sur youtube grâce à ce lien : https://www.youtube.com/watch?v=2IaxbUnoOzo&t=413s
-Ensuite, pour lancer le jeu exécuter le jeu.py dans un terminal ou un IDE.

Les différentes fonctionnalités selon les différents modes de jeu que vous trouverez dans le menu du jeu (partie locale, partie vs ordinateur, partie en ligne (en développement)) :

- Pour tous les modes de jeu, une partie se termine lorsqu’un joueur n’a plus de pions. Un message et un son d'applaudissement vous indiqueront quel joueur à gagné.

-Pour le mode local en cliquant sur le bouton "partie locale":
	
	-> Pour déplacer un pion il vous suffit de cliquer sur le pion que vous souhaitez bouger pour le sélectionner et cliquer sur la case souhaitée.
	-> Il est possible de chevaucher, ou de faire des prises de pions en arrière. Pour cela, quand vous en avez la possibilité, vous devez juste l'activer en cliquant sur le bouton que vous trouverez à votre droite "Chevaucher/Prise en arrière".
	->Pour pouvoir transformer un de vos pions en dame, il suffit d'atteindre l'extrémité du damier adverse.
	->Pour déplacer un dame, cliquez case par case.
	->Le mode local contient aussi la règle du pion soufflé, si vous déplacez un pion alors que celui-ci pouvait prendre un pion, il est donc soufflé(retiré du plateau). Cette règle est activée de base, vous pouvez donc choisir de la désactiver au début du jeu en appuyant sur le bouton "Désactiver pion soufflé".
	->Une fois que votre pion est bougé, il faut appuyer sur le bouton "Fin de tour", pour permettre aux pions adverses de jouer.
	->Un bouton "restart" est à votre disposition pour recommencer une partie, replacer la totalité des pions.
	->Si vous souhaitez changer de mode, le bouton "Menu" vous replacera au menu.
	->Si vous avez un doute sur le fonctionnement du jeu, le bouton "Comment jouer ?" ouvrira une fenêtre à part pour vous aiguiller. 

-Pour le mode contre un ordinateur en cliquant sur le bouton "partie vs ordinateur":

	->Pour déplacer un pion il vous suffit de cliquer sur le pion que vous souhaitez bouger pour le sélectionner et cliquer sur la case souhaitée. Ensuite appuyez sur "fin de tour" et le pion noir sera joué.
	->Il est possible de chevaucher, ou de faire des prises de pions en arrière. Pour cela, quand vous en avez la possibilité, vous devez juste l'activer en cliquant sur le bouton que vous trouverez à votre droite "Chevaucher/Prise en arrière".
	->Pour pouvoir transformer un de vos pions en dame, il suffit d'atteindre l'extrémité du damier adverse.
	->Un bouton "restart" est à votre disposition pour recommencer une partie, replacer la totalité des pions.
	->Si vous souhaitez changer de mode, le bouton "Menu" vous replacera au menu.
	->Si vous avez un doute sur le fonctionnement du jeu, le bouton "Comment jouer ?" ouvrira une fenêtre à part pour vous aiguiller. 

-Pour le mode "partie en ligne":

	-> Comme il est écrit dans le menu, ce mode est en développement, nous avons eu le temps de regarder quelques fonctionnements des sockets avec python, et nous avons juste réussi à faire correspondre deux terminaux.
