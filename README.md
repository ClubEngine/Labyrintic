Labyrintic
==========
*fork issu des idées de la GameJam #6*

*tout est sousmis à modification*

Concept
=======

Une équipe d'une dizaine de joueurs doit survivre dans un labyrinthe
de très grande taille. Cette compagnie est formée de différentes
classes, chacune possédant un gameplay et une interface différente
pour réagir avec l'environnement.

Pas de victoire possible, seulement des records de survie. Les monstres
deviennent de plus en plus nombreux et résistants avec le temps.

durée d'une partie normale: une trentaine de minutes

Caractèristiques du Labyrinthe
==============================

* Très (très) grande taille, généré de façon procédurale,
  éventuellement "infini" ?

* Environnement varié, pas uniquement du couloir / salle,
  éventuellement de l'extérieur dans un second temps.

* Spawn infini de monstres dans les zones sombres (impossible de
  revenir sur ses pas sans re-combattre, le problème "petit poucet"
  grâce aux zones sans monstre est donc réglé)

* Périodes de "frenzy monsters" aléatoires ou suite au déclenchement
  d'un événement. La compagnie doit alors se retrancher pour ne pas
  crever.

* Politique de masse / horde niveau monstres, du style de ce qu'à
  apporté un Left 4 Dead aux jeux de zombies.

Classes
=======

guerrier / combattant
---------------------

Combat de type Hack'n slash, le combattant ne s'équipe pas lui même et
doit protéger ses camarades en limitant le nombre d'ennemis les
atteignant. Posséde un set de compétences et de pouvoirs en fonction de
l'équipement que le looteur lui a équipé. La différentiation éventuelle
en war/rang/wiz se fait donc par l'équipement en majorité et "l'affinité"
du joueur avec cet équipement. Celle-ci chute drastiquement lors d'un
changement d'équipement. 

champ de vision très limité, à la première personne.

(équivalent au joueur de la GJ6)

constructeur
------------

Capable de construire des fortifications pour des camps de protection
lors des périodes de "frenzy monsters" ou lors du cast d'un très gros
spell par le mappeur / l'un des guerriers ou lors du cast d'un revival
d'un des membres (sort nécessitant le cast simultané par 50% de la
compagnie, pendant 10s par exemple)

champ de vision limité, caméra style RTS. Peut être amené à contrôller
plusieurs "unités" de construction ?

Il peut être armé pour se défendre en dernier recours.

looteur / logisticien / carrier
-------------------------------

Il récupére le loot des monstres, il est le seul à avoir un
inventaire. Il peut donc équiper et déséquipper les autres membres de la
compagnie, crafter de nouveaux équipements. Il est en charge de maintenir
les stocks de nourriture, d'eau, d'énergie de la compagnie.

champ de vision moyen, caméra style RTS. Peut être amené à contrôller
plusieurs "unités" carrier ?

Il peut s'armer pour se défendre en dernier recours.

Mappeur / Explorateur
---------------------

Il posséde des sorts couteux et immobilisants (pour la plupart)
d'exploration / découverte / éclaireur / prise de contrôle de monstre
/ visions à longue distance ... en fonction de l'équipement et
du type d'hôte qu'il occupe.

Il "dirige" donc l'avancement de la compagnie et peut cartographier
(via des dessins par exemple) l'avancement de la compagnie pour
qu'elle ne tourne pas en rond.

champ de vision et caméra dépendant de "l'hôte" sélectionné. Il passe
d'hôte en hôte en fonction des entités entourant son dernier hôte.
(Autrement dit il peut faire des sauts d'hôte en hôte pour se ballader
et mapper)

Si l'hôte meurs, il respawn aléatoirement sur l'un des membres contrôllés
par la compagnie.
Si la compagnie n'a plus de "membres" vivants, il est détruit, la
compagnie perd la partie.

(équivalent au maitre du jeu de la GJ6)

Graphismes
==========

3D WebGL, univers plutôt futuriste / post-apo mais je n'y accorde
pas énormément d'importance.

Histoire / Background
=====================

no idea

Facteurs pour l'équilibrage
===========================

* nombre de joueurs dans une compagnie

* collaboration sonore, aucune limitation, les gens se démerdent avec
  du Skype / TS whatever. Possibilité d'évolution vers de la perte
  d'audio à distance, des bruitages de monstres couvrant le son des
  camarades etc ...

* loots

* temps de cast des sorts, sorts à plusieurs etc .. (notamment lors
  d'un revival)



Ceci reste un draft de ce que pourrait être labyrintic, tout est soumis à modification
