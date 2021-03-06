---
title: Rapporto di test con utenti del sito "RAI Friuli Venezia Giulia" | Dettaglio dei Risultati
summary: Rapporto di test con utenti del sito "RAI Friuli Venezia Giulia" | Dettaglio dei Risultati.
authors:
    - Enrico Basso
    - Amos Cappellaro
    - Luca Dal Poz
date: 2019-07-10
---

# Risultati in dettaglio

## Caso d'uso 1  
Consultare il TGR (Tele Giornale Regione) trasmesso la sera precedente.  
**NB**: il test di questo caso d'uso è stato considerato POSITIVO nonostante le repliche dei telegiornali siano rese fruibili tramite il sito nazionale [Rai News](https://rainews.it).

<div class="test-box border-danger">
     <div class="test-box-head bg-danger">
          <h3>Partecipante A</h3>
          <p><strong>Esito: </strong>NEGATIVO</p>
          <p><strong>Tempo impiegato: </strong>1 minuto 45 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Ricerca nel campo "Ricerca" il telegiornale specificando giorno e mese.</li>
               <li>Il campo di ricerca non si svuota, difficoltà nell'inserimento.</li>
               <li>Riceve 43 risultati non inerenti.</li>
               <li>Prova una nuova ricerca aggiungendo l'anno nella query.</li>
               <li>Risultati diversi ma ancora non pertimenti.</li>
               <li>Naviga fino a un box a metà pagina a destra con gli ultimi telegiornali e trova quello della sera precedente.</li>
          </ul>
          <p><strong>Commenti: </strong>
               Si aspettava di trovare il telegiornale tramite la ricerca. Non si riesce a tornare alla homepage dalla pagina di visualizzazione del telegiornale.
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante B</h3>
          <p><strong>Esito: </strong> POSITIVO</p>
          <p><strong>Tempo impiegato: </strong>1 minuto 3 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li> Nella pagina "HOME", click in alto a destra su link "ULTIMO TG". </li>
               <li> Appare box con video streaming di un telegiornale. </li>
               <li> Si accorge che l'ora del risultato non è quella cercata. </li>
               <li> Naviga in fondo alla pagina e click su link al tg con data e ora corrette. </li>
               <li> Visualizza tg tramite box video streaming. </li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante C</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong> 21 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li> Visiona velocemente tutta la pagina "HOME". </li>
               <li> Si accorge della sezione laterale a dx "ULTIMO TGR". </li>
               <li> Click su box relativo al tg con data e ora cercate. </li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-danger">
     <div class="test-box-head bg-danger">
          <h3>Partecipante D</h3>
          <p><strong>Esito: </strong>NEGATIVO</p>
          <p><strong>Tempo impiegato: </strong>2 minuti 40 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click pagina "ULTIMO TGR" ma non trova il TGR desiderato.</li>
               <li>Ricerca nel campo "Ricerca" il telegiornale specificando giorno, mese e anno.</li>
               <li>Il campo di ricerca non si svuota, difficoltà nell'inserimento.</li>
               <li>Riceve 43 risultati non inerenti.</li>
               <li>Click pagina "PROGRAMMI" (Tv)</li>
               <li>Seleziona nel filtro il campo "Programmi Tv"</li>
          </ul>
          <p><strong>Commenti: </strong>
               Si chiede se cliccando su "ULTIMO TGR" si possa raggiungere quello desiderato.
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante E</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong>57 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Naviga fino a fondo pagina ma non trova il TGR.</li>
               <li>Click pagina "ULTIMO TGR".</li>
               <li>Naviga a fondo pagina e trova il TGR della sera precedente.</li>
          </ul>
          <p><strong>Commenti: </strong>
               Pensava di poter trovare gli altri TGR cliccando su "ULTIMO TGR".
          </p>
     </div>
</div>


## Caso d'uso 2  
Trovare l’indirizzo di posta elettronica della Sede Regionale RAI del Friuli Venezia Giulia.

<div class="test-box border-danger">
     <div class="test-box-head bg-danger">
          <h3>Partecipante A</h3>
          <p><strong>Esito: </strong>NEGATIVO</p> (eseguito fuori tempo massimo)
          <p><strong>Tempo impiegato: </strong>2 minuti 10 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Controlla il footer ma non c'è l'indirizzo email desiderato.</li>
               <li>Click pagina "CHI SIAMO".</li>
               <li>Non c'è l'email della sede.</li>
               <li>Click pagina "CONTATTI" ma non c'è l'email della sede.</li>
               <li>Click pagina "LA SEDE".</li>
               <li>Trova l'indirizzo email desiderato.</li>
          </ul>
          <p><strong>Commenti: </strong>
               La mail della sede dovrebbe essere nella pagina "CONTATTI".  
          </p>
     </div>
</div>

<div class="test-box border-danger">
     <div class="test-box-head bg-danger">
          <h3>Partecipante B</h3>
          <p><strong>Esito: </strong> NEGATIVO </p>
          <p><strong>Tempo impiegato: </strong>(rinuncia a) 1 minuti 13 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click su link "CONTATTI" nella barra di navigazione in alto. </li>
               <li>Naviga e visiona con calma i vari contatti presenti. </li>
               <li>Non riesce a trovare la mail desiderata. </li>
               <li>Rinuncia. </li>
          </ul>
          <p><strong>Commenti: </strong>
               Si aspettava di trovare per certo le informazioni desiderate nella pagina "CONTATTI", e successivamente che la email da cercare potesse essere quella della redazione giornalistica.
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante C</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong> 36 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li> Click su link "CONTATTI" nella barra di navigazione in alto. </li>
               <li> Scandisce a colpo d'occhio le varie voci della pagina. </li>
               <li> Si accorge di non trovare l'informazione desiderata. </li>
               <li> Click su link "LA SEDE" nella barra di navigazione in alto. </li>
               <li> Rintraccia la email cercata. </li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-danger">
     <div class="test-box-head bg-danger">
          <h3>Partecipante D</h3>
          <p><strong>Esito: </strong> NEGATIVO </p>
          <p><strong>Tempo impiegato: </strong>(rinuncia a) 2 minuti 20 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click pagina "CHI SIAMO".</li>
               <li>Naviga a fondo pagina, controlla il footer torna su.</li>
               <li>Torna alla homepage. Click pagina "CONTATTI".</li>
               <li>Naviga attentamente fino a fondo pagina ma non trova l'email.</li>
          </ul>
          <p><strong>Commenti: </strong>
               Si aspetta che uniche posizioni dove possa essere l'email siano il footer o la pagina "CONTATTI". Presume si intenda l'email della segreteria.
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante E</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong>1 minuto 24 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click pagina "CONTATTI".</li>
               <li>Naviga fino a fondo pagina, torna su.</li>
               <li>Click pagina "LA SEDE"</li>
          </ul>
          <p><strong>Commenti: </strong>
               Si aspettava il contatto email nella pagina "CONTATTI".
          </p>
     </div>
</div>

## Caso d'uso 3  
Trovare la frequenza radio per sintonizzarsi a RAI Radio1 da Tarvisio.

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante A</h3>
          <p><strong>Esito: </strong>POSITIVO</p>
          <p><strong>Tempo impiegato: </strong>1 minuto 3 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click su "Radio" nella prima navbar in alto e va su sito nazionale della RAI.</li>
               <li>Torna indietro.</li>
               <li>Click pagina "FREQUENZE" e trova la frequenza desiderata.</li>
          </ul>
          <p><strong>Commenti: </strong>
               La prima navbar crea confusione.
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante B</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong> 16 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li> Click su link "FREQUENZE" nella barra di navigazione in alto. </li>
               <li> Naviga e trova l'informazione desiderata. </li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante C</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong> 25 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li> Click su link "FREQUENZE" nella barra di navigazione in alto. </li>
               <li> Naviga e trova l'informazione desiderata. </li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante D</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong>39 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click pagina "FREQUENZE".</li>
               <li>Naviga nella tabella dei comuni.</li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante E</h3>
          <p><strong>Esito: </strong>POSITIVO</p>
          <p><strong>Tempo impiegato: </strong>1 minuto 7 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click pagina "GUIDA TV" (Radio).</li>
               <li>Click su "Scopri la messa in onda di un programma".</li>
               <li>Click pagina "FREQUENZE".</li>
               <li>Naviga nella tabella dei comuni.</li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

## Caso d'uso 4  
Ascoltare l’ultima puntata andata in onda del programma *Rock Revolution*.

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante A</h3>
          <p><strong>Esito: </strong>POSITIVO</p>
          <p><strong>Tempo impiegato: </strong>1 minuto 42 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Ricerca il programma desiderato tramite la  barra di ricerca.</li>
               <li>Nessun risultato. Il partecipante crede che il programma possa non esistere.</li>
               <li>Click pagina "PODCAST".</li>
               <li>Click pagina del programma "Rock Revolution".</li>
          </ul>
          <p><strong>Commenti: </strong>
               Il partecipante non conosceva il significato del termine "podcast".
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante B</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong>1 minuto 24 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li> Scrive "Rock Revolution" nel campo di ricerca sotto la barra di navigazione in alto a dx. </li>
               <li> Non ottiente nessun risultato. </li>
               <li> Click su sezione "PODCAST" a dx della pagina. </li>
               <li> Naviga in basso fino a trovare il programma cercato nell'elenco dei podcast. </li>
               <li> Click su link "ROCK REVOLUTION". </li>
               <li> Naviga e click su pulsante SCARICA relativo alla puntata cercata. </li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante C</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong>1 minuto 13 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li> CLick su link "I PROGRAMMI" sotto la voce "Radio" nella barra di navigazione in alto. </li>
               <li> Click su lettera R della lista dell'alfabeto. </li>
               <li> Cerca e click su programma "Rock Revolution". </li>
               <li> Naviga e click su link "ASCOLTA E SCARICA LE PUNTATE". </li>
               <li> Naviga e click su pulsante SCARICA relativo alla puntata cercata. </li>
          </ul>
          <p><strong>Commenti: </strong>
               Il partecipante in un primo momento, nella pagina del programma con l'elenco delle puntate da scaricare, non considerava il riultato più recente che è ingrigito/scurito di default come facente parte dell'elenco delle puntate.
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante D</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong>2 minuti 54 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click pagina "PROGRAMMI" (Tv).</li>
               <li>Click su "R" della lista alfabetica ma non funziona.</li>
               <li>Click su filtro, seleziona "Programmi tv".</li>
               <li>Ricerca nel campo "Ricerca" le parole "rock revolution".</li>
               <li>Il campo di ricerca non si svuota, difficoltà nell'inserimento.</li>
               <li>Riceve 43 risultati non inerenti.</li>
               <li>Click pagina "PROGRAMMI" (Radio).</li>
               <li>Click su "R" della lista alfabetica.</li>
               <li>Click su "ROCK REVOLUTION".</li>
               <li>Click su "ASCOLTA E SCARICA LE PUNTATE".</li>
               <li>Naviga fino a fondo pagina, torna su.</li>
               <li>Clicca su "SCARICA" dell'ultima puntata.</li>
          </ul>
          <p><strong>Commenti: </strong>
               Intende l'elenco ordinato dalla puntata meno recente (in alto) alla più recente (in basso); non nota il player per ascoltare la puntata in-browser.
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante E</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong>1 minuto 18 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click pagina "PROGRAMMI" (Tv).</li>
               <li>Click su "R" della lista alfabetica ma non funziona.</li>
               <li>Click su filtro, seleziona "Programmi radio".</li>
               <li>Click su "R" della lista alfabetica.</li>
               <li>Click su "ROCK REVOLUTION".</li>
               <li>Click su "ASCOLTA E SCARICA LE PUNTATE".</li>
               <li>Clicca su "SCARICA" dell'ultima puntata.</li>
          </ul>
          <p><strong>Commenti: </strong>
               Confusa dallo sfondo dell'ultima puntata selezionata di default, subito nota la seconda puntata; non nota il player per ascoltare la puntata in-browser.
          </p>
     </div>
</div>

## Caso d'uso 5  
Trovare i contatti (telefono ed email) della persona a capo della conduzione del programma radio *Peter Pan - I Bambini Ci Guardano*.

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante A</h3>
          <p><strong>Esito: </strong>POSITIVO</p>
          <p><strong>Tempo impiegato: </strong>3 minuti 32 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click pagina "CONTATTI". Nessun risultato inerente.</li>
               <li>Ricerca in barra di ricerca il nome del programma.</li>
               <li>43 risultati non inerenti.</li>
               <li>Clicca su risultato "CONTATTI" ma è la stessa pagina visitata prima.</li>
               <li>Click pagina "PODCAST".</li>
               <li>Click pagina "Peterpan - i bambini ci guardano".</li>
               <li>Ci sono solo le puntate però non il nome del conduttore/conduttrice.</li>
               <li>Torna alla homepage. Click pagina "I PROGRAMMI" (Radio)</li>
               <li>Click pagina programma "Peterpan - i bambini ci guardano".</li>
               <li>Trova il contatto della conduttrice.</li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante B</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong>2 minuto 50 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li> Cerca nella pagina "HOME" per diversi secondi per capire dove premere. </li>
               <li> Click su sezione "CONTATTI" nella barrra di navigazione in alto, </li>
               <li> Naviga e si accorge che non contiene l'informazione cercata. </li>
               <li> Scrive "Peter Pan" su campo di ricerca sotto la barra di navigazione a dx. </li>
               <li> Non ottiene nessun risultato. </li>
               <li> Click su link "PROGRAMMI" sotto la voce "Radio" nella barra di ricerca in alto a dx. </li>
               <li> Naviga più in basso fino a trovare il programma desiderato.</li>
               <li> Click su "Peter Pan - I Bambini Ci Guardano". </li>
               <li> Naviga a fondo pagina e trova la email cercata. </li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante C</h3>
          <p><strong>Esito: </strong> POSITIVO </p>
          <p><strong>Tempo impiegato: </strong>1 minuto</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li> Click su pagina "CONTATTI" nella barrra di navigazione in alto. </li>
               <li> Naviga e si accorge che non contiene l'informazione cercata. </li>
               <li> Torna alla pagina "HOME". </li>
               <li> Click su link "PROGRAMMI" sotto la voce "Radio" nella barra di ricerca in alto a dx. </li>
               <li> Click su lettera P della lista dell'alfabeto. </li>
               <li> Cerca e Click su link "Peter Pan - I Bambini Ci Guardano". </li>
               <li> Naviga a fondo pagina e trova la email cercata. </li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante D</h3>
          <p><strong>Esito: </strong>POSITIVO</p>
          <p><strong>Tempo impiegato: </strong>1 minuto 38 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click pagina "PROGRAMMI" (Radio).</li>
               <li>Click su "R" della lista alfabetica.</li>
               <li>Click su "PETER PAN - I BAMBINI CI GUARDANO"</li>
               <li>Naviga a metà pagina</li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>

<div class="test-box border-success">
     <div class="test-box-head bg-success">
          <h3>Partecipante E</h3>
          <p><strong>Esito: </strong>POSITIVO</p>
          <p><strong>Tempo impiegato: </strong>58 secondi</p>
     </div>
     <div class="test-box-body">
          <p><strong>Percorso seguito:</strong></p>
          <ul>
               <li>Click pagina "PROGRAMMI" (Radio).</li>
               <li>Click su "R" della lista alfabetica.</li>
               <li>Click su "PETER PAN - I BAMBINI CI GUARDANO"</li>
               <li>Naviga a metà pagina</li>
          </ul>
          <p><strong>Commenti: </strong>
               [nessuno]
          </p>
     </div>
</div>
