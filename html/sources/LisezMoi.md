# LISEZ-MOI

## Le contenu général :

Les ressources textuelles ayant permis la réalisation des pages html proviennent de la page wikipédia (version française et version anglaise) du groupe et de celle des artistes.

Les photographies proviennent de Ggoogle images. Celles des pochettes de CD proviennent de la rubrique discographie du site internet officiel du groupe.

Cinq vidéos ajoutés à la page videos.html proviennent de Youtube.

Les deux fichiers audio de la page audio.html proviennent de ma discothèque personnelle.

L'ensemble des pages html et la feuille de styles ont été validées par le W3C Validator (html et css).

## Le code HTML5 / CSS :

Le code Html suit une organisation classique, à savoir :

* <head>
* <header>
* <body>
* <div>
* <footer>

Le contenu des cours a été la principale ressource pour la réalisation de ce site web.
Puis, les sites Open Class Room, W3school et W3.org ont été régulièrement consultés, notamment pour le menu et les notes en survol par exemple. Pour mieux comprendre les possibilités de Skeleton, le site www.codepen.io a également été régulièrement visité.

Le site internet a été exploité sous Chrome, Safari, Mozilla Firefox et Internet Explorer.


## Présentation du travail réalisé :

Pour ce devoir, nous devions réaliser un site internet fixe encodé en HTML 5 et CSS, présentant un ariste ou un thème de notre choix.

Outre un intérêt personnel, le choix du groupe de musique australien The John Butler Trio permettait la réalisation de plusieurs pages html alliant textes, son et images. Les données disponibles sur ce groupe sont ni trop importantes (ce qui peut être difficile à gérer) ni pas assez (ce qui aurait appauvri le site internet).

Après la définition du sujet, je me suis attachée à la réalisation d'une maquette, page par page. Pour cela, je suis tout d'abord aller visiter le site internet offciel du groupe, afin de ne pas trop m'en inspirer. Puis, je me suis tournée vers les grandes tendances actuelles en web design ; je souhaitais un site clair, coloré et pratique.

En troisième année de licence en histoire de l'art (parcours documentation), j'ai suivi des cours en html/Css et réalisé un petit site web. Pour aller plus loin et rester fidèle à ma maquette, l'utilisation d'un framework s'est révélée être une bonne alternative, et je ne le regrette pas. Le choix de Skeleton s'est fait rapidement, car il s'agit d'un framework très léger, plutôt accessible pour une première utilisation et permet au site d'être responsive, ce qui était une volonté de ma part.

Hormis la structure propre à Skeleton (sur laquelle je reviendrai), celle de l'html/css reste classique ; le <header>, qui contient la banière, son image et le titre de la page dessus avec effet de transparence, le bouton Menu en haut à droite de la banière qui est mobile; le <footer>, qui contient les icônes des réseaux sociaux propres au groupe de musique, les mentions légales, lien externe, contact et lien pour écouter de la musique. Quatre pages html et une page d'accueil ont été crées (index.html (accueil), memmbres.html, actions et engagements.html, discographie.html et vidéos.html). Afin de permettre l'application de la fenêtre externe pour écouter de la musique, une page audio.html est venue se rajouter aux cinq autres.

Puis, des commentaires ponctuent le code Html et Css, afin de permettre une meilleure compréhension du code, occupant par la même le rôle de "guidelines".

Enfin, j'ai souhaité pousser le détail jusqu'au bout en élaborant un flavicon. J'ai pour cela réutiliser le logo du groupe de musique, déjà utiliser pour le titre de la page d'accueil index.html.

## Difficultés rencontrées et choix retenus (ou non) :

La principale difficulté rencontrée a été de s'adapter au framework Skeleton. Même s'il est simple, il n'est pas évident à manier au premier abord.
Il incombe à l'utilisateur du framework Skeleton de  comprendre comment s'organise la feuille de style. Skeleton fonctionne en grille de douze colonnes avec une largeur maximum de 960 px qui se rétrécit avec le navigateur. La largeur maximum peut être modifiée avec une ligne de CSS, les colonnes seront ainsi redimensionées en conséquence.


Question du son ; par le thème choisi, il m'étais possible de proposer plusieurs supports et médias (photographies, vidéos et sons). J'ai tout d'abord pensé à une lecture automatique de la musique dès l'ouverture de la page index.html, avec, tout de même, la possibilité pour le visiteur d'arrêter la musique. Puis, je me suis rendue compte qu'il était possible de proposer une lecture automatique de la chanson, qui se poursuivrait sur toutes les autres pages de manière ininterrompue (cf. plus haut Sources internet). Mais cette option m'obilgeait à utiliser un autre javaScript et cela fonctionnait un coup sur deux. J'ai donc abandonné cette option.
En naviguant sur des sites internet de musique, j'ai vu que beaucoup proposait la lecture de musique grâce à une petite fenêtre. Un lien discret et souligné en pointillé (comme tous les autres liens texte externes et internes et  du site) dans le Footer de chaque page (sauf audio.html) a donc été conçu. En cliquant dessus, une petite fenêtre s'ouvre et propose l'écoute de deux chansons du groupe. L'avantage principal de cette fenêtre est de ne pas gêner le visiteur ; il peut écouter de la musique en cliquant sur le lien, choisir entre une des deux chansons, arrêter la lecture ou non au cours de sa visite du site.

En ce qui concerne les liens externes, il m'a semblé que leur ouverture dans un nouvel onglet de navigation était la meilleure des solutions car cela n'entrave pas la visite du site internet.

Difficultés pour placer la fenêtre popup en dessous du curseur, pour la dimension des photographies.

haut de page en icône


# SOURCES

## Sources internet :

### design/maquette préalable

[Les grandes tendances du web design 2016](http://fr.wix.com/blog/2016/01/12/les-grandes-tendances-du-web-design-2016/)

### framework

[Skeleton css](http://getskeleton.com)

### superposition texte/image

[css-tricks](https://css-tricks.com/text-blocks-over-image/)

### menu latéral

[w3schools](http://www.w3schools.com/howto/howto_js_sidenav.asp)

### font

[What font is?](http://www.whatfontis.com/)

### couleurs

[Adobe Kuler](https://color.adobe.com)

### audio (popup)

[Stackoverflow](http://stackoverflow.com/questions/22444356/html-open-link-in-new-fixed-size-window)

### audio (musique en continu sur les pages = choix non retenu)

[Stackoverflow](http://stackoverflow.com/questions/15612120/how-do-i-make-an-audio-file-play-continuously-on-all-pages)

### CSS liens

[css-tricks](https://css-tricks.com/child-and-sibling-selectors/)
