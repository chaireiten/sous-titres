Bonjour Henri,

Je te recontacte suite aux échanges que nous avions eu en novembre sur les problèmes liés au sous-titrage des vidéos du projet Sisygambis.

Depuis nous avons pas mal avancé.

Nous avons pu déployer des sous titre en Shimaore et en Kibushi  grâce à l'aide de Christine Coulange et de Ben Saïd à Mayotte

Les résultats sont visibles ici

http://www.lauret.info/subtitles/sample.html

Nous avons utilisé un player video qui fait partie de la galaxie des players video Html 5 disponibles

http://html5video.org/wiki/HTML5_Video_Player_Comparison

il s'agit de VideoJs. L’intérêt de celui ci c'est qu'il est soutenu par Brightcove, qui est une plateforme professionnelle de gestion des vidéos

http://videojs.com/
https://github.com/videojs/video.js
https://www.brightcove.com/fr/

Pour la codification des langage je me suis appuyé sur la codification IANA http://www.iana.org/assignments/language-subtag-registry/language-subtag-registry afin d'utiliser les bons codes.

Les langues Shimaore et Kibushi sont parfaitement définies

Pour le Shimaore
%%
Type: language
Subtag: swb
Description: Maore Comorian
Added: 2009-07-29
%%

http://www-01.sil.org/iso639-3/documentation.asp?id=swb
https://www.ethnologue.com/language/swb
https://fr.wikipedia.org/wiki/Mahorais

et pour le Kibushi

%%
Type: language
Subtag: buc
Description: Bushi
Added: 2009-07-29
%%

http://www-01.sil.org/iso639-3/documentation.asp?id=buc
https://www.ethnologue.com/language/buc
https://fr.wikipedia.org/wiki/Shibushi

Le souci auquel nous sommes confronté est que Youtube et Vimeo ne nous permettent pas d'indiquer des sous-titres dans d'autres langues que celles qui sont prévues par leur système respectif ( ~300 langues pour Youtube et ~80 langues pour Vimeo )

Youtube https://www.youtube.com/watch?v=4FVnb0OknVI

Vimeo https://vimeo.com/191857029

L’idéal serait que nous puissions administrer en tant que publicateur vidéo sur ces 2 plateformes, le menu des sous-titres. Du point de vue de la prise en charge des fichiers sous-titre et des caractères, il ne devrait pas y avoir de problème vu ce que ces plateforme traitent déjà.

En ce qui concerne le Shimaore et le Kibushi ces langues peuvent être écrite en caractères latins ou en caractère arabes

J'ai obtenu le feu vert de Ghislaine pour faire une action au titre de la Chaire ITEN Unesco auprès de Youtube et Vimeo pour les langues mois usitées soit accessible en sous-titrage

Qu'en penses tu ?

Je pense que l'idéal serait de monter une démo en ligne comparative et argumentée pour ensuite solliciter Youtube et Viméo.
