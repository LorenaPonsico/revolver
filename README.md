# revolver

Descripció
Es tracta d'un nombre de jugadors/es que amb un revòlver amb una sola bala al tambor, es disparen al cap.

Les classes a fer són:


Revolver (amb un tambor de 6 buits):
Atributs:
- Posició actual* (posició del tambor on es dispara, pot ser que estigui la bala o no).
- Posició bala (la posició del tambor on es troba la bala).
*Aquestes dues posicions, es generaran aleatòriament.

Mètodes:
- disparar(): retorna true si la bala coincideix amb la posició actual.
- seguentBala(): canvia a la següent posició del tambor.
- informa(): mostra informació del revòlver (posició actual i on està la bala).


Jugador/a:
Atributs
- id (representa el número del jugador, comença en 1)
- nom
- nickname (Comença amb el nom més el seu id, “Jugador/a 1” per exemple)
- viu (indica si està viu o no el jugador)

Mètodes:
- jugar(Revolver r): el jugador/a s'apunta i es dispara, si la bala es dispara, el jugador/a mor.


Joc:
Atributs:
- Jugadors/es (conjunt de Jugadors/es)
- Revolver

Mètodes
- fiJoc(): quan un jugador/a mor, retorna true.
- ronda(): cada jugador/a s'apunta i es dispara, s'informarà de l'estat de la partida (El jugador/a X es dispara, no ha mort en aquesta ronda, etc.)


El nombre de jugadors/es serà decidit per l'usuari/ària, però ha de ser entre 1 i 6. Si no està en aquest rang, per defecte serà 6.
En cada torn un dels jugadors/es, dispara el revòlver, si aquest té la bala, el jugador/a mor i el joc s'acaba.
