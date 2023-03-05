# M3-W3-P2-UpgradeAlbum
Migliora il tuo progetto di Album Musicali creato per W2-P1
 
ESERCIZI:
1) Crea una sezione con Jumbotron e una breve spiegazione / immagine del sito. 
2) Usa una Card di Bootstrap per contenere ogni album nella lista dei preferiti che hai creato in precedenza.
Usa gli elementi che la card di Bootstrap ti fornisce per visualizzare correttamente elementi come: titolo dell’album, artista, anno, ecc..
3) Per ogni album nei preferiti aggiungi un badge nell’angolo in alto a destra col genere musicale. 
4) Crea una nuova sezione con le tracce dell’album in una tabella di Bootstrap. I colori delle linee della tabella dovranno essere alternati. Dovrà esserci una colonna per il numero di traccia, titolo, nome artista, durata della traccia. (puoi aggiungerne anche altre) 
5) Aggiungi un bottone “ELIMINA” di colore rosso (usa utility class di Bootstrap) al termine di ogni linea della lista. Attaccaci la funzionalità per rimuovere l’intera riga quando cliccato. (DOM manipulation)  
6) Crea un bottone “Aggiungi traccia” sotto alla tabella delle tracce.
Dovrà avere una transizione di stile per aggiungergli un’ombra quando il bottone riceve l’hover. (box-shadow) 
Dovrà dare come minimo l’impressione di elevarsi da un piano. (aggiungi altri effetti a piacimento)
 
7) Quando “Aggiungi traccia” viene premuto dovrà comparire un modale.
    (fai riferimento all’esempio di modale collegato al click di un bottone)
      
Il modale dovrà contenere input singoli (no <form>) con:
1.	Numero della traccia
2.	Titolo della traccia
3.	Nome dell’artista
4.	Durata della traccia
I campi dovranno essere raggruppati e divisi in due colonne come l’esempio di seguito:
 
 
EXTRA 
Il modale dovrà contenere due bottoni in basso:
●	Aggiungi => Aggiungerà una nuova traccia nella tabella con i dati estratti dagli input del modale. (DOM manipulation)
●	Chiudi => Chiuderà il modale e resetterà i campi.
Quando una nuova traccia viene aggiunta, notifica l’utente con un messaggio dentro un alert contenente il nome della traccia appena aggiunta.
 
CSS EXTRA
●	Crea un effetto fade-in per il jumbotron dell’Es. 1, l’animazione dovrà avvenire al caricamento della pagina. Usa JavaScript per farlo iniziare al momento giusto.
●	Per i bottoni ELIMINA creati nell’Es. 5, fai in modo che sia visibile solo uno per volta quando la sua corrispondente linea riceve l’hover dell’utente. Anima la comparsa del bottone con un effetto di fade-in / fade-out.
