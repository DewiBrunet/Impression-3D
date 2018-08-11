# Impression-3D
Mon aventure dans le monde de l'impression 3D.
C’est un grand pas franchi parce que la 3D, ça fait peur et ça me semble être un des skills technologiques les plus dur à maitriser....     
![images 1](https://user-images.githubusercontent.com/25649502/41813548-64884fc0-7738-11e8-993a-8bcc2eeb6cc0.jpg)

Pourquoi j’en ai besoin ?
-	Pour mes futures œuvres « oribotiques » (engrenage et système de mouvement)
-	Pour compléter mes compétences nécessaires à l’enseignement des nouvelles technologies (pour le projet Fablab Mobile notamment)
-	Pour exécuter des jobs pour OpenFab
-	Pour des réparations
-	 Pour des goodies

Par quoi commencer ?
Faut savoir qu’il y a 2 parties dans l’impression 3D :
1)	La partie logicielle de conception 3D (CAO conception assistée par ordinateur)
2)	La partie machine d’impression 3D

1)	Allez, go pour la partie logicielle ! En fait…

<img src="https://user-images.githubusercontent.com/25649502/43995608-72f80d80-9db1-11e8-8def-67fdf4c6cb73.jpg" alt="alt text" width="150" height="100">

Sur la partie logiciel, je m’y mettrais plus tard, mon utilisation limitée est quasi comblée avec la quantité de fichiers opensource qu’on trouve sur internet (thingiverse,…). J’aurai éventuellement besoin d’ajustements légers sur logiciel de conception 3D.
La création d’un scanner 3D est aussi une option alléchante.  

2)	La partie machine    
Tout commence par une mise en application sur le tas, dans le cadre d’une animation que je donne avec le projet Fablab Mobile. Le cadre est confortable : les machines sont prêtent, les fichiers aussi et il y a des makers compétents avec moi  Journée 1 : démo et explication d’impression 3D sur une Fabrikator II, journée 2 : explication sur logiciel de conception 3D facile (SculptGL) et lancement de fichiers à imprimer à partir de banques de fichiers trouvés sur le net.
<img src="https://user-images.githubusercontent.com/25649502/43995609-7317e556-9db1-11e8-9e57-49f95c2a4528.jpg" alt="alt text" width="300" height="400">


Je lance quelques impressions déjà enregistrées, facile, faut juste ouvrir le logiciel « CURA » qui fait l’interface entre le logiciel de conception 3D et la machine. CURA permet de générer du « gcode » (le langage que lit la machine) et de définir les paramètres d’impressions.

<img src="https://user-images.githubusercontent.com/25649502/43995852-365b0a20-9db7-11e8-81ae-9b8b9ffb62de.png" alt="alt text" width="300" height="200">

Je retrouve au niveau du logiciel CURA, entre autres : 
-	la température de l’extrudeur (la tête qui fond et envoi le plastique)
-	la température du lit (qui reçois le plastique et le durcit doucement)
-	La vitesse d’impression
-	Le remplissage (le degré de plastique pour l’intérieur de la pièce)
-	Le modèle de machine auquel c’est envoyé…

Une fois qu'on sais gérer les quelques paramètres important, il faut juste :
- une machine (ici des « Fabricator », petite machine à +/-200 euros)
-	du filament de plastique (ici du PLA, dérivé du maïs qui doit être biseauté pour mieux s’enfiler)
-	du scotch pour l’adhérence sur le tapis

J’ai un cas de « filament bouché » sur une machine… Aucun souci, faut juste retirer le filament de PLA, le rebiseauter puis le réenfiler et pousser en chauffant l’extrudeur pour entrainer le fil. J’ai pas vraiment eu d’autres problèmes mais des interrogations apparaissent sur les paramètres machine, l’utilité du sotch, la capacité d’impression… Mais ça finit très bien avec une impression de la « Chain Mail » développée par la NASA !    
<img src="https://user-images.githubusercontent.com/25649502/43995610-73372cae-9db1-11e8-86da-29f5935e70e6.jpg" alt="alt text" width="300" height="400">

2 semaines passent sans que je retouche à l’impression 3D mais me revoilà replongé dans une situation à débrouillardise nécessaire : je dois assurer l’accueil et la gestion des impressions 3D pour OpenFab.

Easy, ça doit être la même chose que sur les Fabrikators du Fablab Mobile, une fois que je sais lancer sur une machine je sais lancer sur toutes !   
Oui et non      
Oui, on passe par CURA à OpenFab (puis faut mettre ça sur micro sd dans la machine).      
Non, c’est pas exactement les mêmes machines, les paramètres CURA encodés sont différents.      

Il y a 2 machines, l’une tombe en rade rapidement en voulant changer de couleur de filament, l’autre fonctionne bien. Je lance un long job (40h) pour un client OpenFab et tout ce passe bien. Puis je veux lancer des petits engrenages pour moi mais le filament ne sort pas vraiment comme il faut…       
<img src="https://user-images.githubusercontent.com/25649502/41813493-79524cb8-7737-11e8-8228-791453ec7e55.jpg" alt="alt text" width="300" height="200">      
*si quelqu'un sais comment faire pivoter une image sur Github je suis preneur ;)

Recommandé par SatLouis, je vais voir sur https://www.simplify3d.com/support/print-quality-troubleshooting/ Une magnifique FAQ qui contient bien évidemment des solutions à mon problème. C’est fréquent, faut recalibrer pour que tout soit parallèle et la tête de l’extrudeur au ras du tapis (pouvoir passer une feuille de papier).      
Ok donc il y a un ou plusieurs axe qui ont bougé (dû à la gravité ou au fait que le dernier job soit resté allumé longtemps ?), faut les remettre droit en vissant ou dévissant.   
Oui mais l’axe de l’extrudeur ou le tapis d’impression ?   
Pff, va pour le second. Il y a 4 visses vertes, faut juste bien vérifier avec une règle pour avoir un écartement uniforme. Easy, ça redémarre.   

Allez, je peux lancer mes engrenages ! Je laisse les options de CURA, on verra bien.

Youpi, ça fonctionne :)   
<img src="https://user-images.githubusercontent.com/25649502/43995987-dcba6076-9db9-11e8-8956-6c0d9d9c4384.png" alt="alt text" width="200" height="200">

MAIS :
Premier constat : vérifier la taille/l’épaisseur/l’utilité du tapis    
<img src="https://user-images.githubusercontent.com/25649502/43995614-7484e34e-9db1-11e8-898d-35f50418ec38.jpg" alt="alt text" width="300" height="200"> <img src="https://user-images.githubusercontent.com/25649502/43995613-745d4604-9db1-11e8-85e2-53960ad08734.jpg" alt="alt text" width="300" height="200">

--> J'ai créé un TUTO Choix du tapis pour ça (avec surtout ce qu'il faut pas faire^^) :       
https://github.com/DewiBrunet/Impression-3D/blob/master/Importance%20du%20tapis.md


Deuxième constat : haha, pas si facile la calibration…

Troisième constat : comme tout les outils, faut apprendre à gérer les paramètres.


Mais quelle expérience l’impression 3D ! En termes de création c’est bizarrement très gratifiant, une certaine magie se dégage.

<img src="https://user-images.githubusercontent.com/25649502/43996136-a43393dc-9dbc-11e8-824d-0ef83a5604e6.jpg" alt="alt text" width="200" height="200">

Essayons de mettre l’autre machine en route maintenant. Enlever, biseauter, remettre, chauffer, pousser, pousser… et ça plusieurs fois, rien n’y fait. J’essaye aussi une technique recommandée par Nico : un fil de cuivre enfilé par la sortie de l’extrudeur pour enlever les crasses coincées.

Et une chose étrange se passe : le filament ressort sur un côté de la machine. Avide de savoir, je décide de démonter délicatement cette partie pour y voir plus clair. C’est bien avec ça, je comprends mieux la manière dont le filament est entrainé, la ventilation. Le filament restant est bien visible à l’entrée de la vis. J’essaye d’en enlever le maximum, remonte le tout, recalibre, biseaute, enfile, chauffe et pousse, pousse… rien n’y fait.

On m’expliquera plus tard que c’est sans doute le filament qui est coupé au mauvais endroit, où ça ne chauffe pas. La seule solution serait d’ouvrir la tête de l’extrudeur.

TUTO Déboucher une buse : https://github.com/DewiBrunet/Impression-3D/blob/master/D%C3%A9boucher%20buse.md

Mais bref, une fonctionne et je compte bien continuer à lancer des impressions !
C’est parti pour la découverte des textiles imprimées en 3D…


<img src="" alt="alt text" width="300" height="200">
