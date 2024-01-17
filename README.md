# VistTracker
<table><tr><td>
<b>Resume</b>
<br>
Do what Google Analytics does but provide more details on the visitor's journey on your site.
<br>
<b>Keywords:</b> <i>PHP, Laravel</i>
</td></tr></table>

## Context
Ayant des difficultés avec Google analytics sur mon site et cherchant à avoir plus d'options et la main sur ce que j'ai comme statistiques, j'ai développé _VisitTracker_. Vù que mon site est en CMS Prestashop basé sur PHP, j'ai développé le script de suivi en PHP et MySQL. Le frontend a été développé en Laravel par un collègue. 

## Comment ça fonctionne
_VisitTracker_ récupère les informations principalement de la signature de l'agent de l'explorateur du visiteur mais aussi du site, il les enregistre ensuite dans une base de données tout en vérifiant s'il s'agit d'un nouveau visiteur ou une nouvelle page ouverte par un utilisateur déjà enregistré, d'un robot ou humain. Le front end est alimenté avec cette base, où on peut filtrer les visits selon plusieurs critères: Pays, date, type (robot ou non), etc.. Il suffit ensuite de cliequer sur _détails_ pour avoir plus d'informations sur les pages visités par un utilisateur.

### Fonctionnalités 
- Les informations enregistrées pour chaque visiteur: ips utilisées,	name (si authentifié sur le site),	start time,	end time,	nombre de pages,	country,
- Les informations de chaque page: type de page (dans le site), url, referer (url précédente), l'agent (signature de l'explorateur),
- Mise en évidence les visits suspects selon des critères prédéfinis (nombre de page, signature, pays.

![image](https://github.com/elho2007/VisitTrack/assets/34011591/2c2565df-8152-44fc-9cf4-18600337a4b8)

Vous pouvez voir le frontend [ici](http://vtrack.gpsuite.co.uk)

### À venir
- Une vidéo démonstratif,
- Plus de détails sur le développement de *VisitTracker*,
