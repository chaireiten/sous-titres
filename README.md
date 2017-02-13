* Sous Titrage pour le Web
* Players Video HTML 5
* Codification des langues
* Exemple de Mayotte
* Codage des sous-titres en Shimaoré et en Kibushi
* Problématique de YouTube et de Vimeo  

### Sous Titrage pour le Web

Le soustitrage des vidéos est défini dans le standard HTML5

Le document WebVTT: The Web Video Text Tracks Format détaille les spécifications du standard

https://w3c.github.io/webvtt/
  

### Players Video HTML 5

La plupart des players vidéo HTML5 modernes offrent la possibilité de gérer les sous-titres au format standard .vtt

http://html5video.org/wiki/HTML5_Video_Player_Comparison

Pour l'expérimentation nous avons utilisé le player VideoJs. L’intérêt de celui ci c'est qu'il est soutenu par Brightcove, qui est une plateforme professionnelle de gestion des vidéos

http://videojs.com/  
https://github.com/videojs/video.js  
https://www.brightcove.com/fr/  


### Codification des langues

Pour la codification des langages, la nomenclature IANA référence plus de 7000 langues

http://www.iana.org/assignments/language-subtag-registry/language-subtag-registry afin d'utiliser les bons codes.


### Exemple de Mayotte
 
Les langues Shimaore et Kibushi sont parfaitement définies dans les codifications internationales.

En ce qui concerne le Shimaore et le Kibushi, ces langues peuvent être écrites en caractères latins ou en caractères arabes.

|                    | Shimaore                                                                                        | Kibushi                                                                                         |
|--------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| IANA : Type        | language                                                                                        | language                                                                                        |
| IANA : Subtag      | swb                                                                                             | buc                                                                                             |
| IANA : Description | Maore Comorian                                                                                  | Bushi                                                                                           |
| IANA : Added       | 2009-07-29                                                                                      | 2009-07-29                                                                                      |
| Graphies           | Latines, Arabes                                                                                 | Latines, Arabes                                                                                 |
| Ref                | http://www-01.sil.org/iso639-3/documentation.asp?id=swb https://www.ethnologue.com/language/swb | http://www-01.sil.org/iso639-3/documentation.asp?id=buc https://www.ethnologue.com/language/buc |
| Wikipedia          | https://fr.wikipedia.org/wiki/Mahorais https://en.wikipedia.org/wiki/Maore_dialect              | https://www.ethnologue.com/language/buc https://en.wikipedia.org/wiki/Bushi_language            |


### Codage des sous-titres en Shimaoré et en Kibushi

Nous avons pu déployer des sous titre en Shimaore et en Kibushi grâce à l'aide de Christine Coulange et de Abdoul-Karime Ben Saïd du MUMA à Mayotte

Les résultats sont visibles ici

http://www.lauret.info/subtitles/index.html


### Problématique de YouTube et de Vimeo

Youtube et Vimeo ne nous permettent pas d'indiquer des sous-titres dans d'autres langues que celles qui sont prévues par leur système respectif (~300 langues pour Youtube et ~80 langues pour Vimeo)

Youtube et Vimeo n'ont pas pris en compte le Shimaore et le Kibushi dans leurs dispositifs de traduction et / ou de gestion des sous-titres.

Translator Toolkit de Google

https://translate.google.com/toolkit/docupload?hl=fr

Langues des sous titres supportées par Viméo

https://vimeo.com/help/faq/managing-your-videos/captions-and-subtitles#what-languages-does-vimeo-support-for-captions-and-subtitles

Il n'est pas possible de sous titrer les videos dans ces langues sur les 2 plateformes
 
Youtube : https://www.youtube.com/watch?v=4FVnb0OknVI

Vimeo : https://vimeo.com/191857029

L’idéal serait que nous puissions administrer en tant que publicateur vidéo sur ces 2 plateformes, le menu des sous-titres. Du point de vue de la prise en charge des fichiers sous-titres et des caractères, il ne devrait pas y avoir de problème car ces plateformes traitent déjà la plupart des encodages Unicode pour les sous-titres déjà supportés.



