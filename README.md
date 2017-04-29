il codice caricato sulla piattaforma riguardera la con-correnza (e' il verificarsi di eventi allo stesso tempo "contemporaneamente"
per citare un nostro vecchi progetto vi pongo un esempio Supponiamo che piu' utenti debbano usare il registro elettronico, se il programma fosse progettatto senza usare la programmazione concorrenziale (multithreading), solo un utente alla volta sarebbe in grado di accedervi.
ma cos'è un thread ? beh un thread è e' una porzione di un programma che viene eseguito contemporaneamente ad altre porzioni dello stesso programma.
Spesso THREADs comunicano, condividono risorse, collaborano e hanno parte di codice in comune.
esempio: il registro elettronico che permette a piu' utenti di accedervi contemporaneamente
uno strumento informatico che permette a piu' processi di essere in esecuzione contemoporaneamete e' detto multi-threading
per portarvi un esempio molto più pratico carichero un codice in cui sono presenti tre thread (tic,tac,toe) quest'ultimi hanno un compito molto semplice scandire un conto alla rovescia però alternandosi in modo casuale come in esempio:
Main Thread iniziata...
<TAC> TAC: 10
<TOE> TOE: 10
<TIC> TIC: 10
<TAC> TAC: 9
<TOE> TOE: 9
<TAC> TAC: 8
<TIC> TIC: 9
<TAC> TAC: 7
<TOE> TOE: 8
<TIC> TIC: 8
e via dicendo il tempo è parzialmente casuale poiche è comunque un numero tra 100 e 300 ms
questo è un esempio molto semplice ma questo è nulla rispetto al vero potenziale della programmazione con-corrente.
