---
title: Rapporto conformità WCAG 2.1 "vatican.va"
summary: Rapporto conformità WCAG 2.1 del sito "vatican.va".
authors:
    - Enrico Basso
    - Amos Cappellaro
    - Luca Dal Poz
date: 2019-07-10
---

# Draft report

[TOC]

## 1 PERCEPIBILE

### 1.1 Alternative Testuali

#### 1.1.1 Contenuti non testuali

SINTOMO
Persone che hanno difficoltà a capire il significato delle frecce, non possono essere aiutate dalla tecnologia assistiva a capirne l'utilizzo.
CAUSA
Non sono presenti spiegazioni testuali per l'utilizzo dei bottoni per la navigazione tra le pagine.
Immagine di esempio
Codice

```html
 <a href="#" onclick="javascript:history.go(-1);return false;">
      <img border="0" src="/etc/designs/vatican/library/images/back.png" width="30" height="30" alt="Back" title="Back">
  </a>
  <a href="#" onclick="javascript:history.go(-1);return false;">
      <img border="0" src="/etc/designs/vatican/library/images/top.png" width="30" height="30" alt="Top" title="Top">
  </a>
  <a href="#" onclick="self.print(); return false;">
      <img border="0" src="/etc/designs/vatican/library/images/print.png" alt="Print" title="Print" width="26" height="26">
  </a>
```
POSSIBILI RIMEDI
Aggiungere una spiegazione utilizzando delle aria-label per fare in modo che il lettore di schermo possa indicare la funzione dei link (tag <a>).
Codice di esempio

```html
<button class="arrLeft" aria-label="Indietro"></button>
<button class="arrRight" aria-label="Avanti"></button>

<a href="#" aria-label=“Indietro” onclick="javascript:history.go(-1);return false;">
  <img border="0" src="/etc/designs/vatican/library/images/back.png" width="30" height="30" alt="Back" title="Back">
</a>
<a href="#" aria-label=“Top” onclick="javascript:history.go(-1);return false;">
  <img border="0" src="/etc/designs/vatican/library/images/top.png" width="30" height="30" alt="Top" title="Top">
</a>
<a href="#" aria-label=“Stampa” onclick="self.print(); return false;">
  <img border="0" src="/etc/designs/vatican/library/images/print.png" alt="Print" title="Print" width="26" height="26">
</a>
```
### 1.2 Media Temporizzati
#### 1.2.1 Solo audio e video (preregistrati)
#### 1.2.2 Sottotitoli (preregistrati)
#### 1.2.3 Audiodescrizione o tipo di media alternativo (preregistrato)
#### 1.2.4 Sottotitoli (in tempo reale)
#### 1.2.5 Audiodescrizione (preregistrata)
#### 1.2.6 Lingua dei segni (preregistrato)
#### 1.2.7 Audiodescrizione estesa (preregistrata)
#### 1.2.8 Tipo di media alternativo (preregistrato)
#### 1.2.9 Solo audio (in tempo reale)
### 1.3 Adattabile
#### 1.3.1 Informazioni e correlazioni
SINTOMO
La navigazione può risultare difficile per chi utilizza la tastiera e i lettori di schermo.
CAUSA
I livelli di heading non vengono rispettati.

Codice
<h1>
    <a>Attività del Santo Padre Francesco</a>
</h1>
<h3>Archivio Eventi</h3>

POSSIBILI RIMEDI
Seguire l'ordine degli heading facendo in modo che non vengano saltati livelli.

        1.3.2 Sequenza significativa

        1.3.3 Caratteristiche sensoriali ???
SINTOMO
Persone cieche o con limitata capacità visiva potrebbero non capire come utilizzare il componente di ricerca.
CAUSA
Il pulsante che permette di inviare la richiesta di ricerca, per far capire all'utente la sua funzione, si basa solo sulla forma, la posizione e il carattere contenuto.

Codice
<input type="submit" value="»" name="go">

POSSIBILI RIMEDI
Aggiungere informazione testuale in aggiunta a quella visiva, per esempio tramite l'attributo HTML title e/o aria-label.
Codice di esempio
<input type="submit" value="»" name="go" aria-label="vai">


#### 1.3.4 Orientamento
#### 1.3.5 Identificare lo scopo degli input
SINTOMO
Persone cieche o con limitata capacità visiva potrebbero non capire come utilizzare il componente di ricerca.
CAUSA
Il lettore di schermo non raggiunge nè il titolo della sezione di ricerca ‘Archivio eventi’, nè le voci del select. Risulta difficile, dunque, identificare uno scopo dell’elemento input.
Immagine di esempio
POSSIBILI RIMEDI
Facilitare la lettura e la selezione dell’anno, mese e giorno per la ricerca da tastiera.

#### 1.3.6 Identificare lo scopo (vedi 2.4.9)
SINTOMO
Persone cieche o con limitata capacità visiva potrebbero non capire lo scopo di alcune icone.
CAUSA
Il lettore di schermo non specifica il fine delle icone di condivisione.
Immagine di esempio
Codice

<a href="#" onclick="javascript:shareOnFacebook();return false;">
              <img src="/etc/designs/vatican/library/images/share/facebook.png" alt="Facebook" title="Facebook">
          </a>
POSSIBILI RIMEDI
Utilizzare tag ARIA
Codice d’esempio
<a href="#" onclick="javascript:shareOnFacebook();return false;">
              <img src="/etc/designs/vatican/library/images/share/facebook.png" alt="Facebook" title="Facebook" aria-label=“condividi su Facebook">
          </a>



    1.4 Distinguibile
        1.4.1 Uso del colore
SINTOMO
Persone con problemi nella visualizzazione dei colori potrebbero non percepire lo stato in cui un elemento è in focus.
CAUSA
Il colore e l’opacità sono utilizzati come unica modalità visiva per rappresentare alcune informazioni.
Immagine di esempio

POSSIBILI RIMEDI
Utilizzare il css per fornire altre informazioni oltre al colore, per esempio utilizzare la proprietà text-decoration per aggiungere la sottolineatura.
Codice d’esempio
a:active, a:hover {text-decoration:underline;}


        1.4.2 Controllo del sonoro
        1.4.3 Contrasto (minimo)
Verificato tramite il tool WAVE
Immagine di prova

        1.4.4 Ridimensionamento del testo
        1.4.5 Immagini di testo
        1.4.6 Contrasto (avanzato)
        1.4.7 Sottofondo sonoro basso o non presente
        1.4.8 Presentazione visiva
CAUSA
I colori del testo in primo piano e dello sfondo non possono essere scelti dall’utente.
        1.4.9 Immagini di testo (senza eccezioni)
        1.4.10 Ricalcolo del flusso
        1.4.11 Contrasto in contenuti non testuali
Verificato tramite il tool WAVE
        1.4.12 Spaziatura del testo
        1.4.13 Contenuto con Hover o Focus



2 UTILIZZABILE
    2.1 Accessibile da tastiera
        2.1.1 Tastiera
SINTOMO
Persone cieche o con limitata capacità visiva e quelle con tremori di mano tali da non poter usare il mouse, non riescono ad usufruire pienamente del sito.
CAUSA
Non tutte le funzionalità del contenuto sono utilizzabili tramite un'interfaccia di tastiera a causa dell’utilizzo di eventi attivabili solo da mouse e gestiti tramite jquery:
Non è possibile consultare l’orario degli eventi in programma
Non è possibile passare al mese precedente o successivo nel calendario
Non è possibile effettuare alcuna ricerca in Archivio Eventi

POSSIBILI RIMEDI
Aggiungere la possibilità di attivare le funzionalità anche con evento keydown().

        2.1.2 Nessun impedimento all’uso della tastiera
        2.1.3 Tastiera (nessuna eccezione)
        2.1.4 Tasti di scelta rapida
    2.2 Adeguata disponibilità di tempo
        2.2.1 Regolazione tempi di esecuzione
        2.2.2 Pausa, stop, nascondi
        2.2.3 Nessun tempo di esecuzione
        2.2.4 Interruzioni
        2.2.5 Riautenticazione
        2.2.6 Termine del tempo
    2.3 Convulsioni e reazioni fisiche
        2.3.1 Tre lampeggiamenti o inferiore alla soglia
        2.3.2 Tre lampeggiamenti
        2.3.3 Animazione da interazioni
    2.4 Navigabile
        2.4.1 Salto di blocchi
        2.4.2 Titolazione della pagina
        2.4.3 Ordine del focus
        2.4.4 Scopo del collegamento (nel contesto) ???
SINTOMO
Persone con capacità cognitive limitate sono disorientate dai multipli link con significato ambiguo.
CAUSA
Nella pagina sono presenti icone che talvolta portano alla stessa pagina.
Inoltre, nella lista delle attività, gli elementi di classe .baloon e i titoli a fianco riportano alla stessa pagina.
POSSIBILI RIMEDI
Dare una breve descrizione della pagina di destinazione delle icone.
Rendere cliccabile solo i titoli delle attività.

        2.4.5 Differenti modalità
SINTOMO
Persone cieche o con limitata capacità visiva o con capacità cognitive limitate sono disorientate dai diversi layout di pagine dello stesso sito.
CAUSA
Nel sito sono presenti pagine con layout completamente differenti.
POSSIBILI RIMEDI
Uniformare le pagine ad un unico layout condiviso.

        2.4.6 Intestazioni ed etichette
SINTOMO
La navigazione può risultare difficile per chi utilizza la tastiera e i lettori di schermo.
CAUSA
Assenza di etichette.
POSSIBILI RIMEDI
Popolare gli elementi della pagina con etichette che li descrivano.
        2.4.7 Focus visibile
        2.4.8 Posizione
        2.4.9 Scopo del collegamento (vedi 1.3.6)
SINTOMO
Persone cieche o con limitata capacità visiva potrebbero non capire lo scopo di alcune icone.
CAUSA
Il lettore di schermo non specifica il fine delle icone di condivisione.
Immagine di esempio
Codice
<a href="#" onclick="javascript:shareOnFacebook();return false;">
              <img src="/etc/designs/vatican/library/images/share/facebook.png" alt="Facebook" title="Facebook">
          </a>
POSSIBILI RIMEDI
Utilizzare tag ARIA
Codice d’esempio
<a href="#" onclick="javascript:shareOnFacebook();return false;">
              <img src="/etc/designs/vatican/library/images/share/facebook.png" alt="Facebook" title="Facebook" aria-label=“condividi su Facebook">
          </a>

        2.4.10 Intestazioni di sezione
    2.5 Modalità di input
        2.5.1 Movimenti del puntatore
        2.5.2 Cancellazione delle azioni del puntatore
        2.5.3 Etichetta nel nome
        2.5.4 Azionamento del movimento
        2.5.6 Meccanismi di input simultanei
SINTOMO

CAUSA

Immagine di esempio

POSSIBILI RIMEDI



3 COMPRENSIBILE
    3.1 Leggibile
        3.1.1 Lingua della pagina
SINTOMO
Le persone con disabilità potrebbero non capire bene il contenuto della pagina perché il lettore di schermo potrebbe non leggere con la pronuncia corretta le parole.
CAUSA
Il linguaggio della pagina non è determinato programmaticamente.
POSSIBILI RIMEDI
Inserire l’attributo lang nel tag HTML.
Codice di esempio
<!DOCTYPE html>
<html lang="it”>

        3.1.2 Parti in lingua
        3.1.3 Parole inusuali
SINTOMO
È possibile che non vengano comprese alcune parti della pagina perché non viene data la definizione per parole poco comuni ed inusuali.
CAUSA
Utilizzo di parole inusuali
POSSIBILI RIMEDI
Utilizzare l’attributo abbr ed aggiungere la definizione della parola nell’attributo title ???
        3.1.4 Abbreviazioni
parole
SINTOMO
Le persone con disabilità potrebbero non capire bene il contenuto della pagina.
CAUSA
Alcune parole sono scritte in maniera abbreviata
Immagine di esempio
Codice
<div class="bweek">Dom</div>
POSSIBILI RIMEDI
Utilizzare il tag abbr.
Codice di esempio
<abbr class="bweek" title=“Domenica”>Dom</abbr>
        3.1.5 Livello di lettura
        3.1.6 Pronuncia
    3.2 Prevedibile
        3.2.1 Al focus
        3.2.2 All’input
        3.2.3 Navigazione coerente (vedi 2.4.5)
        3.2.4 Identificazione coerente
        3.2.5 Cambiamenti su richiesta
    3.3 Assistenza nell’inserimento
        3.3.1 Identificatore di errori
        3.3.2 Etichette o istruzioni
SINTOMO
Gli utenti con disabilità cognitive non riescono ad utilizzare lo strumento di ricerca. Il lettore di schermo non dà informazioni sull’utilizzo.
CAUSA
Gli utenti non hanno adeguati suggerimenti per le operazioni di input per il form di ricerca nell’Archivio Eventi.
Codice
<select name="year" style="display: none;">
<option value="">Anno</option>
<option value="2018">2018</option>
<option value="2019">2019</option>
</select>
POSSIBILI RIMEDI
Inserire <label> associata al select per la ricerca.
Codice di esempio ???
<select name="year" style="display: none;">
<label for="googleText">Seleziona l’anno della ricerca</label>
<option value="">Anno</option>
<option value="2018">2018</option>
<option value="2019">2019</option>
</select>

        3.3.3 Suggerimenti per gli errori
        3.3.4 Prevenzione degli errori (legali, finanziari, dati)
        3.3.5 Aiuto
        3.3.6 Prevenzione degli errori (tutti)


4 ROBUSTO
    4.1 Compatibile
        4.1.1 Analisi sintattica (parsing)
SINTOMO
La tecnologia assistiva non riesce a parsare e interpretare il contenuto adeguatamente.
CAUSA
Il codice HTML non è ben formato. La correttezza del codice è stata controllata con validatore HTML e ha dato in output 2 errori e 9 warning (in data 11/07/19).
POSSIBILI RIMEDI
Utilizzare HTML in accordo con le specifiche e verificare la correttezza del codice con validatori online. Sistemare gli errori che vengono riscontrati per far sì che il codice risulti corretto.
        4.1.2 Nome, ruolo, valore
SINTOMO
La tecnologia assistiva non riesce ad interpretare nel modo corretto il form.
CAUSA
Per il form sono stati utilizzati elementi HTML che non sono interpretabili dalla tecnologia assistiva.
Codice
<span id="" class="selectboxit-container selectboxit-container" role="combobox" aria-autocomplete="list" aria-haspopup="true" aria-expanded="false" aria-owns="">
    <span id="" class="selectboxit  selectboxit-enabled selectboxit-btn" name="year" tabindex="0" unselectable="on" style="width: 235px;">
        <span class="selectboxit-option-icon-container">
            <i id="" class="selectboxit-default-icon selectboxit-option-icon selectboxit-container" unselectable="on"></i>
        </span>
        <span id="" class="selectboxit-text" unselectable="on" data-val="" aria-live="polite" style="max-width: 205px;">Anno</span>
        <span id="" class="selectboxit-arrow-container" unselectable="on">
            <i id="" class="selectboxit-arrow selectboxit-default-arrow" unselectable="on"></i>
        </span>
    </span>
    <ul class="selectboxit-options selectboxit-list" tabindex="-1" role="listbox" aria-hidden="true" style="min-width: 235px;">
        <li data-id="0" data-val="" data-disabled="false" class="selectboxit-option  selectboxit-option-first selectboxit-selected" role="option">
            <a class="selectboxit-option-anchor">
                <span class="selectboxit-option-icon-container">
                    <i class="selectboxit-option-icon  selectboxit-container"></i>
                </span>Anno
            </a>
        </li>
        <li data-id="1" data-val="2013" data-disabled="false" class="selectboxit-option" role="option">
            <a class="selectboxit-option-anchor">
                <span class="selectboxit-option-icon-container">
                    <i class="selectboxit-option-icon  selectboxit-container"></i>
                </span>2013
            </a>
        </li>    
POSSIBILI RIMEDI ???
Non utilizzare elenchi, div e span ma utilizzare i tag form, select e option, associando ad ogni select una label.
Codice di esempio
<form>
     <label for=“anno”>Anno</label>
     <select id=“anno”>
        <option>2013</option>
        …
        <option>2019</option>
    </select>
     …
</form>
        4.1.3 Messaggi di stato
