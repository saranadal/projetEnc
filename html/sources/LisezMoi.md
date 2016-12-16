# LISEZ-MOI

## Organisation des fichiers

```
.
|
+—— /html/
|   |
|   +—— index.html
|   |
|   +—— membres.html
|   |
|   +—— actionsEtEngagements.html
|   |
|   +—— audio.html
|   |
|   +—— discographie.html
|   |
|   +—— videos.html
|   
+—— /css/
|   |
|   +—— style.css
|   |
|   +—— /skeleton/
|       |
|       +—— normalize.css
|       |
|       +—— skeleton.css
|
+—— /js/
|   |
|   +—— scriptJs.js
|
+—— /medias/
|   |
|   +—— /audio/
|   |   |
|   |   +—— peachesCream.mp3
|   |   |
|   |   +—— springToCome.mp3
|   |
|   +—— /images/ (les images sont trop nombreuses pour être listées)
|
+—— /sources/
|   |
|   +—— LisezMoi.md
|   |
|   +—— LisezMoi.pdf (généré à partir du Markdown)
```

## Le contenu général :

Les ressources textuelles ayant permis la réalisation des pages html proviennent de la page Wikipédia (version française et version anglaise) du groupe et de celle des artistes.

Les photographies proviennent de Google images. Celles des pochettes de CD proviennent de la rubrique discographie du site internet officiel du groupe.

Cinq vidéos ajoutées à la page videos.html proviennent de Youtube.

Les deux fichiers audio de la page audio.html proviennent de ma discothèque personnelle (à ne pas diffuser).

L'ensemble des pages html et la feuille de style ont été validées par le W3C Validator (html et css).

L'ensemble du dossier html est enregistré et disponible sur Github à cette adresse : (https://github.com/saranadal/projetEnc).

L'éditeur de texte ATOM a été utilisé pour l'ensemble de ce travail.

## Le code HTML5 / CSS :

Le code Html suit une organisation classique, à savoir :
```xml
<html/>
|
+——<head/>
|
+——<body/>
|   |
|   +——<header/>
|   |
|   +——<div/>
|   |   |
|   |   +——contenu
|   |
|   +——<footer/>
```

Le contenu des cours a été la principale ressource pour la réalisation de ce site web.
Puis, les sites [Open Class Room](https://openclassrooms.com/
), [W3school](www.w3schools.com) et [W3.org](www.w3.org) ont été régulièrement consultés, notamment pour le menu et les notes en survol par exemple. Pour mieux comprendre les possibilités de Skeleton, le site [codepen.io](www.codepen.io) a également été régulièrement visité et s'est révélé très utile.

Enfin, le site internet a été exploité sous Chrome, Safari et Mozilla Firefox.


## Présentation du travail réalisé :

Pour ce devoir, nous devions réaliser un site internet fixe encodé en HTML 5 et CSS, présentant un artiste ou un thème de notre choix.

Outre un intérêt personnel, le choix du groupe de musique australien The John Butler Trio permettait la réalisation de plusieurs pages html alliant textes, son et images. Les données disponibles sur ce groupe sont ni trop importantes (ce qui peut être difficile à gérer) ni insuffisante (ce qui aurait appauvri le site internet).

Après la définition du sujet, je me suis attachée à la réalisation d'une maquette, page par page. Pour cela, je suis tout d'abord aller visiter le site internet officiel du groupe, afin de ne pas trop m'en inspirer. Puis, je me suis tournée vers les grandes tendances actuelles en web design ; je souhaitais un site clair, coloré, pratique et dans l'air du temps.

En troisième année de licence en histoire de l'art (parcours documentation), j'ai suivi des cours en html/Css et réalisé un petit site web. Pour aller plus loin et rester fidèle à ma maquette, l'utilisation d'un framework s'est révélée être une bonne alternative, et je ne le regrette pas. Le choix de Skeleton s'est fait rapidement, car il s'agit d'un framework très léger, plutôt accessible pour une première utilisation. De plus, il permet au site d'être responsive, ce qui était une volonté de ma part, afin d'adapter le site aux besoins des visiteurs (site consultable sur ordinateur, sur smartphone et tablette tactile).

Hormis la structure propre à Skeleton (sur laquelle je reviendrai), celle de l'Html/Css reste classique ; le ``<header>``, qui contient la bannière, son image et le titre de la page dessus avec effet de transparence, le bouton Menu en haut à droite de la bannière qui est mobile ; le ``<footer>``, qui contient les icônes des réseaux sociaux propres au groupe de musique, les mentions légales, liens externes, contact et lien pour écouter de la musique. Quatre pages html et une page d'accueil (index.html) ont été créées : membres.html, actions et engagements.html, discographie.html et vidéos.html. Afin de permettre l'application de la fenêtre externe pour écouter de la musique, une page audio.html est venue se rajouter aux cinq autres.

Puis, des commentaires ponctuent le code Html et Css, afin de permettre une meilleure compréhension du code, occupant par la même le rôle de « *guidelines* ».

Après, je me suis appliquée à l'élaboration d'un flavicon. J'ai pour cela réutiliser le logo du groupe de musique, déjà utilisé pour le titre de la page d'accueil index.html.

Enfin, la réalisation de ce travail a été l'occasion d'apprendre à utiliser le terminal de mon ordinateur et les commandes propres à Github, car l'ensemble du travail a été régulièrement enregistré sur le site. Pour moi, cet outil de travail est important, puisqu'il s'agit « d'un dépôt social pour les projets open-source […] qui permet de partager du code facilement et de collaborer sur des projets ». Pour permettre au visiteur du site internet d'avoir accès à Github et aux codes et fichiers, je me suis permise d'ajouter le logo du site internet dans le ``<footer>`` qui, lorsque l'on clique dessus, ouvre le lien de mon compte dans un nouvel onglet.

## Difficultés rencontrées et choix retenus (ou non) :

Tout d'abord, la principale difficulté rencontrée a été de m'adapter au framework Skeleton. Même s'il est simple, il n'est pas évident à manier au premier abord.
Il incombe à l'utilisateur du framework Skeleton de  comprendre comment s'organise la feuille de style. Skeleton fonctionne en grille de douze colonnes avec une largeur maximum de 960 px qui se rétrécit avec le navigateur. La largeur maximum peut être modifiée avec une ligne de CSS, les colonnes seront ainsi redimensionées en conséquence.

Puis, pour le menu déroulant, je me suis permise d'appliquer un script, afin d'obtenir un menu qui apparaît et disparaît selon les besoins du visiteur. N'ayant jamais fait de javaScript, je suis allée chercher le scritp sur internet (Cf. Sources en ligne).

Ensuite, s'est posée la difficultée des vidéos. Le groupe The John Butler Trio dispose de sa propre chaîne sur Youtube et poste de nombreuses vidéos. J'ai souhaité en montrer un échantillon. L'une d'entre elle ne fonctionnait pas si je n'utilisais pas la balise ``<iframe>`` (obsolète). En réalité, c'est le propre code de la vidéo qui n'était pas valide.
==>J'ai donc changé la vidéo et cela a fonctionné.

Après, c'est la redimension des vidéos qui posait problème. Je souhaitais que les vidéos apparaissent en grand, avec leur titre placé en dessous.
==>J'ai finalement placé les vidéos dans une ``<div>`` avec une ``class="twelve columns"`` afin de prendre toute la grille Skeleton. Puis j'ai attribué une taille à la vidéo dans le code Html (``height="500" width="1000"``) et une ``class="video"`` à l'élément ``<figure>`` et ``<object>`` pour le Css, me permettant de redimensionner le contenant de la vidéo et son contenu.

Puis, j'ai rencontré des difficultés avec le son. Grâce au thème choisi, il m'était possible de proposer plusieurs supports et médias (photographies, vidéos et sons). J'ai tout d'abord pensé à une lecture automatique de la musique dès l'ouverture de la page d'accueil index.html avec, tout de même, la possibilité pour le visiteur d'arrêter la musique. Puis après quelque recherche, je me suis rendue compte qu'il était possible de proposer une lecture automatique de la chanson, qui se poursuivrait sur toutes les autres pages de manière ininterrompue (cf. Sources en ligne). Mais cette option m'obligeait à utiliser un autre javaScript et cela fonctionnait un coup sur deux. J'ai donc abandonné cette option.
==>En naviguant sur des sites internet de musique, j'ai vu que beaucoup proposait la lecture de musique grâce à une petite fenêtre. Un lien discret et souligné en pointillé (comme tous les autres liens texte externes et internes du site) dans le ``<footer>`` de chaque page (sauf audio.html) a donc été conçu. En cliquant dessus, une petite fenêtre s'ouvre et propose l'écoute de deux chansons du groupe. L'avantage principal de cette fenêtre est de ne pas gêner le visiteur ; il peut écouter de la musique en cliquant sur le lien, choisir entre une des deux chansons, arrêter la lecture ou non au cours de sa visite du site.

Ensuite, j'ai testé mon site internet sur différents navigateur. Celui qui m'a posé quelques soucis est Mozilla Firefox. En effet, sur ce navigateur les liens ancres pour les vidéos fonctionnent mal : lorsque l'on est sur la page actionsEtEngagements.html, les liens internes proposés qui renvoient à trois vidéos de la page videos.html ne coïncident pas et sont décalées. Je me suis d'abord demandé si ce n'était pas dû à la faiblesse du réseau internet à mon domicile mais cela focntionne parfaitement sur les autres navigateurs.
==>Je n'ai pas su ni pu régler ce problème.

En ce qui concerne les liens externes, il m'a semblé que leur ouverture dans un nouvel onglet de navigation était la meilleure des solutions car cela n'entrave pas la visite du site internet. Ceci ne m'a pas posé de problème particulier.

Enfin, j'ai trouvé l'exercice des commentaires du code peu évident au début. Je me suis efforcée de faire coïncider les commentaires des pages Html avec ceux de la feuille de style.




## Sources en ligne

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
