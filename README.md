# site-de-voyage

Intégration d'un site de voyage en HTML/CSS.


CONTEXTE :

L’entreprise souhaite développer un site Internet qui permette aux usagers de trouver des hébergements et des activités dans la ville de leur choix. 
Vous êtes chargé d'intégrer l'interface du site avec du code HTML et CSS. Pour cela, je devais travailler en étroite collaboration avec Sarah, la CTO, 
et Loïc, l’UI designer.


Notes de Synthèse :

Voici l’ensemble des points fonctionnels et techniques à prendre en compte pour le développement du nouveau site Booki.
L’ensemble de ces éléments a été validé par l’équipe Produit, il est important de les respecter.


Spécifications fonctionnelles:

• Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être édité par l’utilisateur.

• Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité (pas uniquement le titre).

• Les filtres doivent changer d’apparence au survol. Par contre, ils ne doivent pas être fonctionnels - il s’agit d’une première version pour valider l’interface..

• Les liens “Hébergements” et “Activités”Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens.
Ils doivent mener respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.


Spécifications techniques :

• Trois maquettes ont été réalisées : desktop, tablette et mobile. (First version destok), puis tablettes et enfin téléphones)

• Nous avons convenu avec le designer UI d’utiliser 992 px et 768 px :
=992 px pour les écrans d’ordinateurs ; =768 px pour les tablettes ; et tout ce qui est en dessous de 768 pour les téléphones portables.

• Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir déterminer une largeur maximum de 1 400 px.

• L’utilisation des Media Queries nous permettra de réaliser l’intégration pour les différents supports.

• Les icônes proviennent de la bibliothèque Font Awesome.

• Les couleurs de la charte sont le bleu (#0065FC), une version plus claire de ce bleu (#DEEBFF) et le gris pour le fond (#F2F2F2).

• La police du site est Raleway. Nous pouvons passer par Google Fonts.

• Il est recommandé d'utiliser Flexbox.
