[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/DbCtJu4d)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11096498&assignment_repo_type=AssignmentRepo)
# sesion7-tarea-individual

ENDEVINA UN NÚMERO!

Fes un algorisme amb el PSeInt que trie un número secret a l'atzar i que l'usuari haja d'endevinar-lo en diversos intents.

Concretament, caldrà fer el següent:

- Calcular un número aleatori (secret) entre 1 i 100. Ho pots fer amb la funció "Aleatorio". Per exemple:
   	secret = Aleatorio(1, 100)

- Demanar per teclat una quantitat màxima d'intents (per a endevinar el número).

- Demanar per teclat el número diverses vegades fins que l'encerte o fins que l'usuari haja usat tots els intents.

- Després de cada intent, es mostrarà una pista: "És major" o "És menor". A més, també es mostrarà el nou rang de possibles valors. 


- En acabar la partida caldrà mostrar un d'estos 2 missatges (segons el cas):
	- Has superat els intents. No ho has endevinat. El número era el 33.
O bé:
	- Molt bé! Ho has encertat en 5 intents. 

- Es preguntarà si vol jugar una altra partida. Si es contesta 's' o 'S' es tornarà a fer tot el procés (calcular número aleatori, etc). Si no, acaba el programa.

