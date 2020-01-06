# Anamorphoses_animees

Vous trouverez ci-après les fichiers utilisés pour créer une anamorphose animée des arrondissements de Bogotá (capitale de la Colombie) (http://espenf.cnrs.fr/AnamorphoDyn).

Ces derniers peuvent être déformés selon six catégories d'ICS distinctes (Indice de condition sociale).

La carte a été réalisée dans le cadre d'une analyse portant sur les différents outils disponibles aujourd'hui pour la réalisation d'anamorphoses animées.


Parmi les fichiers disponibles, vous trouverez :
  - Localidades_multipart.json : fichier correspondant au fond de carte
  - localidad_bogota_4.csv     : fichier correspondant aux données liées au fond de carte
  - index.html                 : fichier html à executer  
  - cartogram.js               : fichier javascript comprenant l'algorithme de Dougenik & al. pour construire une anamorphose 
  - colorbrewer.js             : fichier pour le choix des couleurs des cartes choroplèthes, basé sur le travail du Dr. Cynthia Brewer
  - topojson_old.js            : fichier pour lire les fichiers au format TopoJSON
  - AnimationD3_Bogota_ICS.gif : fichier correspondant au résultat obtenu à partir des autres fichiers au format GIF 


</br>
</br>


Ce travail a été réalisé par Mégane BOUQUET dans le cadre d'une mission encadrée par Florent DEMORAES. Ce travail est inspiré de celui d'Etienne COME avec la "France du Bon Coin"(http://www.comeetie.fr/map_lbc.php) et de celui de Raphael DA SILVA (https://blog.m0le.net/2013/10/20/autopsie-dune-dataviz-3-une-carte-en-anamorphose-avec-champs-de-selection/).
