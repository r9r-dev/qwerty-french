# French (QWERTY-FRENCH)

Clavier français QWERTY. Ce projet est librement inspiré du projet "qwerty-fr" créé par Paul @devnoname120. Suite aux nombreuses modifications apportées depuis la version 0.6, j'ai décidé de créer un nouveau projet qui se rapproche d'avantage de mes usages. Ceci n'est pas un fork, j'ai repris le projet à zéro.

# Fondamentaux

Cette disposition respecte les fondamentaux d'une disposition mise à disposition du public.

## Immuable

En premier lieu, elle est **immuable**. La version originale du projet a déplacé certaines touches comme les `ê` ce qui me semble une abberation. Dans l'hypothèse où une nouvelle version demanderai de déplacer ou de modifier le comportement des touches existantes, une nouvelle disposition avec un autre nom sera alors créée à part.

Les seules autorisations de modification seront donc les ajouts là où il y a de la place.

## Francophone

qwerty-frENCH est davantage destiné aux francophones. A trop vouloir contenter de langues, je pense que le projet original s'est petit à petit éloigné de son intérêt de base, à savoir simplifier la saisie de texte en français.

## Simple

qwerty-frENCH est simple. Les caractères couramment utilisés comme `€`, `£` ou `°` sont conservés et ne sont pas considérées comme des touches mortes. De plus, la plupart des caractères de langues étrangères ont été retirés. Elles seront ajoutées à nouveau si on m'en fait la demande et que celle-ci me semble justifiée.

Les touches mortes, souvent source de confusions, sont globalement abandonnées. A voir si on peut les réintroduire plus tard de manière plus intuitive.

# Ecrire avec qwerty-frENCH

## Le layout

Voici le layout qwerty-frENCH.

![qwerty-frENCH](img/layout.png)

## Comment ça marche ?

Grâce aux bonnes idées du projet original, taper les caractères les plus courants de la langue française est d'une grande simplicité.

Chaque caractère A, E, I, O et U peuvent être accentués en respectant une direction.

![accents](img/accents.png)

- `AltGr` + `E` pour `è`
- `AltGr` + à gauche de `E` pour `é`
- `AltGr` + au dessus de `E` pour `ê`
- `AltGr` + en dessous de `E` pour `ë`

Voir la section [Apprendre à taper avec qwerty-frENCH](#apprendre-à-taper-avec-qwerty-french) pour plus de détails.

## Le respect du clavier international

qwerty-frENCH tente de respecter en partie le clavier US international pour ne pas trop changer vos habitudes. Les touches `€` `²`, `³` et `µ` conservent donc leurs positions. J'ai par contre du déplacer certains caractères comme `©` ou `£` mais les raisons sont expliquées plus bas.

## Le côté pratique

Ma philosophie derrière cette disposition est de favoriser au maximum l'écriture tout en permettant d'accéder aux caractères les plus courants dans notre monde moderne. Par exemple, je n'ai jamais tapé le caractère n tilde `ñ` de ma vie (pardon aux espagnols). En revanche, je peux être ammené à utiliser la livre sterling `£`, le yen `¥` ou le won `₩` de temps en temps. Voir pourquoi pas le symbôle du bitcoin `₿` ou de l'ether `Ξ` ?

Si je veux exprimer quelques variables, je peux utiliser des caractères grecs comme alpha `ɑ`, beta `ꞵ` ou delta `ẟ`. En mathématiques, on peut avoir à utiliser le nombre pi `π`, parfois aussi le symbôle omega `Ω` pour les mesures de resistance électrique. Enfin, pour les plus fous, on peut utiliser le symbôle de l'infini `∞` (à la place du symbole not sign qui me semble ne servir à rien `¬`). Evidement, on ne perd pas de vue les bonnes idées du projet qwertyfr original avec `×`, `÷`, `≠`ou encore`≈` bien pratiques de temps en temps.

Au dessus des exposants `¹`, `²` et `³`, j'ai redonné leur place aux `¼`, `½` et `¾` qui peuvent aussi parfois être utiles à mon sens. C'est peut-être les trois caractères les moins utiles du clavier. À ses positions, ils restent assez faciles à retenir.

Pour l'écriture inclusive, nous conservons le point médian `·` très pratique en accès direct avec `AltGr` + `.`.

Enfin, on y pense assez peu souvent mais écrire des flèches peut s'avérer toujours pratique. On peut donc écrire `→`, `←`, `↑` et `↓` directement.

# Apprendre à taper avec qwerty-frENCH

Le layout qwerty-frENCH est facile à apprendre grâce à son système de clusters. Comme stipulé plus haut, il suffit de retenir la direction à partir d'un caractère donné pour obtenir une version alternative.

Pour chaque cluster, en appuyant sur `AltGr` le comportement est toujours le même.

![clusters](img/clusters.png)

- Sur la touche, ce sera soit le caractère avec un accent grave ou un caractère spécial
- A gauche, ce sera toujours le caractère avec un accent aigu
- Au dessus, ce sera toujours le caractère avec un accent circonflexe
- En dessous, ce sera soit le caractère avec un tréma ou la version "collée", soit `æ` ou `œ`.

Si vous tapez sur une touche avec `AltGr` et que le résultat n'est pas parmi les règles ci-dessus, c'est qu'il n'est pas utilisé dans la langue française. Par exemple, si vous tapez `AltGr` + `U`, vous obtiendrez `ù` mais cela ne fonctionne pas pour `AltGr` + `O` vu que `ò` n'est pas utilisé dans la langue française. Ainsi, il a été remplacé par un caractère spécial (le symbole `omega` `Ω`).

## Le cluster A

Le cluster A fonctionne de manière normale pour `à` (`AltGr` + `A`) et `â` (`AltGr` + `Q`). A droite, vous obtiendrez `alpha` `ɑ` et en dessous, le caractère `æ`.

![clusterA](img/cluster-a.png).

## Le cluster E

Le cluster E est le plus simple.

![clusterE](img/cluster-e.png).

## Les cluster U, I et O

Les clusters U, I et O fonctionnent de manière similaire. Ils disposent tous de leur version avec accent circonflexe au dessus. En dessous, le tréma est utilisé. Seul le cluster O fait exception avec `Ω` et `œ` en dessous.

![clusterUIO](img/clusters-uio.png).

## Les autres clusters

Presque toutes les touches du clavier s'inspirent de ce système de cluster pour vous aider à les mémoriser. Les clusters C et B sont deux bons exemples. B a deux caractères spéciaux `₿` et `ꞵ`. Tandis que C a `ç` et `©`.

![clusterCB](img/clusters-cb.png).
