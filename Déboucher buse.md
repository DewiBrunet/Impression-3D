« Impossible de pousser le filament dans la buse »  
« Le filament ressort à chaque fois un peu n'importe ou »    
« j’ai tout essayé, je pige pas »     
https://github.com/openfab-lab/openfab/issues/209

Le filament doit s'extruder de manière fluide, droite.      
Si le fil qui sort est dévié ou ne sort pas, c'est qu'une crasse bloque la buse.          

### Voilà ce qu’il faut d’abord essayer :
1.	Vérifier électroniquement si le filament s’extrude : position => move axis => 1mm => extruder
2.	Chauffer à 120°, enfoncer un filament à chaux quelques instants et l'extraire d'un coup bref. Couper le bout, recommencer et observer ce bout pour voir si des crasses sont emportées. 
3.	Chauffer à 120°, enfoncer un filament à chaux quelques instants, laisser refroidir la buse et extraire le fil.
4.	Chauffer, prendre un fil de cuivre (fil émaillé 0.3mm), 30cm suffisent, et le glisser par le trou de la buse (avec des gants ou une pince). Curer la buse en passant le fil entièrement plusieurs fois, le fil va emporter les restes de vieux plastique. 

Si aucune de ses options ne fonctionne, alors il faut démonter la buse et enlever manuellement le bouchon.

<img src="https://user-images.githubusercontent.com/25649502/43995717-73f7dd80-9db3-11e8-826e-7600849b1e23.jpg" alt="alt text" width="400" height="300">    <img src="https://user-images.githubusercontent.com/25649502/43995713-73975924-9db3-11e8-815e-10c5009769c0.jpg" alt="alt text" width="400" height="300">

- Dévisser les vis du bas pour enlever le ventilateur en face    
- Dévisser le ventilateur de gauche    
- Dévisser la plaque    
- Dévisser l’extruder (une vis en bas, un cylindre en haut)    

Attention à bien vérifier toutes les vis et où elles se placent (comme avec Ikea, je me suis retrouvé à la fin avec une vis en trop^^)    
<img src="https://user-images.githubusercontent.com/25649502/43995714-73b7bce6-9db3-11e8-974d-62cbf362868d.jpg" alt="alt text" width="300" height="300"> 
<img src="https://user-images.githubusercontent.com/25649502/43995727-bb3d5efe-9db3-11e8-961f-eb3fb3e74777.jpg" alt="alt text" width="300" height="300"> 

Avec une pince, maintenir la buse et la chauffer avec un décapeur thermique (et prévoir un support pour éviter de toucher des fils ou des axes de la machine). 
Une fois à température, passer un petit coup pour pousser le filament. Essayer ensuite avec un nouveau filament biseauté. Rechauffer autant de fois que nécessaire. Ça devrait pousser le bouchon.
Ne pas hésiter à bien nettoyer la buse avec le fil de cuivre.      
<img src="https://user-images.githubusercontent.com/25649502/43995716-73d8303e-9db3-11e8-82af-dd5fc0c2a69d.jpg" alt="alt text" width="300" height="350">  


Si après tout ça, ou si le fil de cuivre ne passe ps du tout, alors il faut démonter et changer la buse. Y en a dans une boîte au-dessus de l'étagère avec les imprimantes.
