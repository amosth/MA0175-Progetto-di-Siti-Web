---
title: Rapporto di conformità WCAG 2.1 del sito "La Santa Sede" | Dettaglio dei risultati: Livello AA
summary: Rapporto di conformità WCAG 2.1 del sito "La Santa Sede" | Dettaglio dei risultati: Livello AA.
authors:
    - Enrico Basso
    - Amos Cappellaro
    - Luca Dal Poz
date: 2019-07-10
---

# Dettaglio risultati: conformità WCAG 2.1 livello AA

<br>
[[Salta indice](#1-percepibile)]

## Indice

[TOC]

## 1. Percepibile

Le informazioni e i componenti dell'interfaccia utente devono essere presentati agli utenti in modi in cui essi possano percepirli.


### Linea guida 1.2 Media temporizzati

Fornire alternative per i media temporizzati.


<div class="success-criteria success-criteria-warning">
     <h4>Criterio di successo 1.2.4 Sottotitoli (in tempo reale)</h4>
     <p>Per tutti i contenuti audio in tempo reale sotto forma di media sincronizzati sono forniti sottotitoli.</p>
     <br>
     <p><strong>Esito: NON VALUTABILE</strong></p>
</div>

<div class="success-criteria success-criteria-warning">
     <h4>Criterio di successo 1.2.5 Audiodescrizione (preregistrata)</h4>
     <p>Per tutti i contenuti video preregistrati sotto forma di media sincronizzati è fornita una audiodescrizione.</p>
     <br>
     <p><strong>Esito: NON VALUTABILE</strong></p>
</div>


### Linea guida 1.3 Adattabile

Creare contenuti che possano essere rappresentati in modalità differenti (ad esempio, con layout più semplici), senza perdere informazioni o struttura.


<div class="success-criteria  success-criteria-success">
     <h4>Criterio di successo 1.3.4 Orientamento</h4>
     <p>La visualizzazione e il funzionamento di un contenuto non dipendono dall'orientamento dello schermo, ad esempio verticale o orizzontale, a meno che questo non sia essenziale.</p>
     <br>
     <p><strong>Esito: POSITIVO</strong></p>
</div>

<div class="success-criteria">
     <h4>Criterio di successo 1.3.5 Identificare lo scopo degli input</h4>
     <p>Lo scopo di ciascun campo di input per le informazioni sull'utente può essere determinato programmaticamente quando: il campo di input ha uno scopo noto, identificato nella sezione scopo dell'input per i componenti dell'interfaccia utente; e il contenuto è implementato utilizzando tecnologie che supportino l'identificazione del significato atteso dei dati inseriti del modulo.</p>
</div>


### Linea guida 1.4 Distinguibile

Rendere più semplice agli utenti la visione e l'ascolto dei contenuti, separando i contenuti in primo piano dallo sfondo.


<div class="success-criteria">
     <h4>Criterio di successo 1.4.3 Contrasto (minimo)</h4>
     <p>La rappresentazione visiva del testo e di immagini contenenti testo ha un rapporto di contrasto di almeno 4.5:1, fatta eccezione per i seguenti casi: testo grande, testo non essenziale, logotipi.</p>
</div>

<div class="success-criteria success-criteria-success">
     <h4>Criterio di successo 1.4.4 Ridimensionamento del testo</h4>
     <p>Il testo, ad eccezione dei sottotitoli e delle immagini contenenti testo, può essere ridimensionato fino al 200 percento senza l'ausilio di tecnologie assistive e senza perdita di contenuto e funzionalità.</p>
     <br>
     <p><strong>Esito: POSITIVO</strong></p>
</div>

<div class="success-criteria success-criteria-danger">
     <h4>Criterio di successo 1.4.5 Immagini di testo</h4>
     <p>Se le tecnologie utilizzate consentono la rappresentazione visiva dei contenuti, per veicolare informazioni è usato il testo, e non le immagini di testo, ad eccezione dei seguenti casi: personalizzabile, essenziale.</p>
     <br>
     <p><strong>Esito: NEGATIVO</strong></p>
</div>

<br/>

<strong>SINTOMO</strong>  
Nella pagina "Bollettino Stampa" utenti con deficit visivo potrebbero non leggere tutto il contenuto della pagina.

<strong>CAUSA</strong>  
Al centro della pagina è presente un immagine contenente del testo che non si può ridimensionare e che non è leggibile dalle tecnologie assistive. L'attributo "alt" inserito nel link dell'immagine non è sufficiente per descrivere l'intera immagine.

<strong>POSSIBILE SOLUZIONE</strong>  
Utilizzare un'immagine di testo e migliorare la descrizione dell'immagine.

<div class="success-criteria">
     <h4>Criterio di successo 1.4.10 Ricalcolo del flusso</h4>

     <p>Il contenuto può essere ripresentato senza perdita di informazioni o funzionalità e senza richiedere lo scorrimento in due dimensioni per: contenuto a scorrimento verticale con una larghezza equivalente a 320 CSS pixel, contenuto a scorrimento orizzontale ad un'altezza equivalente a 256 CSS pixel. Tranne per le parti del contenuto che richiedono layout bidimensionale per l'utilizzo o per comprenderne il senso.</p>
</div>

<div class="success-criteria">
     <h4>Criterio di successo 1.4.11 Contrasto in contenuti non testuali</h4>

     <p>Nella presentazione visiva il rapporto di contrasto è di almeno 3:1 rispetto al colore o ai colori adiacenti per: componenti dell'interfaccia utente, oggetti grafici.</p>
</div>

<div class="success-criteria">
     <h4>Criterio di successo 1.4.12 Spaziatura del testo</h4>

     <p>Nei contenuti implementati utilizzando linguaggi di markup che supportano le seguenti proprietà di stile per il testo, non si verifica alcuna perdita di contenuto o funzionalità impostando quanto segue senza modificare altre proprietà di stile: altezza della linea (interlinea) di almeno 1,5 volte la dimensione del carattere, spaziatura dopo i paragrafi di almeno 2 volte la dimensione del carattere, spaziatura tra le lettere di almeno 0,12 volte la dimensione del carattere, spaziatura tra le parole di almeno 0,16 volte la dimensione del carattere.

     Eccezione: le lingue e le scritture che non utilizzano una o più di queste proprietà nel testo scritto sono conformi quando si può applicare il criterio alle sole proprietà esistenti per quella combinazione di lingua e scrittura.</p>
</div>

<div class="success-criteria">
     <h4>Criterio di successo 1.4.13 Contenuto con Hover o Focus</h4>

     <p>Nel caso in cui il passaggio del puntatore del mouse (hover) o il focus della tastiera rendono visibili e nascosti dei contenuti, sono soddisfatte le seguenti condizioni: congedabile, passabile, persistente.

     Eccezione: la presentazione visiva del contenuto aggiuntivo è controllata dal programma utente e non viene modificata dall'autore.</p>
</div>


## 2. Utilizzabile

I componenti e la navigazione dell'interfaccia utente devono essere utilizzabili.


### Linea guida 2.4 Navigabile

Fornire delle funzionalità di supporto all'utente per navigare, trovare contenuti e determinare la propria posizione.


<div class="success-criteria">
     <h4>Criterio di successo 2.4.5 Differenti modalità</h4>

     <p>Rendere disponibili più modalità per identificare una pagina Web all'interno di un insieme di pagine Web, salvo il caso in cui una pagina Web sia il risultato – o una fase – di un'azione.</p>
</div>

<div class="success-criteria success-criteria-danger">
     <h4>Criterio di successo 2.4.6 Intestazioni ed etichette</h4>
     <p>Utilizzare intestazioni ed etichette per descrivere argomenti o finalità.</p>
     <br>
     <p><strong>Esito: NEGATIVO</strong></p>
</div>

<br/>

<strong>SINTOMO</strong>  
La navigazione può risultare difficile per chi utilizza la tastiera e i lettori di schermo.

<strong>CAUSA</strong>  
All'interno della pagina non esiste una struttura corretta di instestazioni e non vengono utilizzate etichette per i forms.

<strong>POSSIBILE SOLUZIONE</strong>  
Utilizzare correttamente le intestazioni e le etichette.

<div class="success-criteria success-criteria-success">
     <h4>Criterio di successo 2.4.7 Focus visibile</h4>
     <p>Qualsiasi interfaccia utente utilizzabile tramite tastiera ha una modalità operativa in cui è visibile l'indicatore del focus.</p>
     <br>
     <p><strong>Esito: POSITIVO</strong></p>
</div>


## 3. Comprensibile

Le informazioni e le operazioni dell'interfaccia utente devono essere comprensibili.


### Linea guida 3.1 Leggibile

Rendere il testo leggibile e comprensibile.


<div class="success-criteria success-criteria-danger">
     <h4>Criterio di successo 3.1.2 Parti in lingua</h4>
     <p>La lingua di ogni passaggio o frase nel contenuto può essere determinata programmaticamente ad eccezione di nomi propri, termini tecnici, parole in lingue indeterminate e parole o frasi che sono diventate parte integrante del gergo del testo immediatamente circostante.</p>
     <br>
     <p><strong>Esito: NEGATIVO</strong></p>
</div>

<strong>SINTOMO</strong>  

<strong>CAUSA</strong>  

<strong>POSSIBILE SOLUZIONE</strong>  


### Linea guida 3.2 Prevedibile

Creare pagine Web che abbiano aspetto e funzionamento prevedibili.


<div class="success-criteria success-criteria-success">
     <h4>Criterio di successo 3.2.3 Navigazione coerente</h4>
     <p>I meccanismi di navigazione che sono ripetuti su più pagine Web all'interno di un insieme di pagine Web, appaiono nello stesso ordine relativo ogni volta che si ripetono, a meno che un cambiamento sia stato avviato da un utente.</p>
     <br>
     <p><strong>Esito: POSITIVO</strong></p>
</div>

<div class="success-criteria success-criteria-success">
     <h4>Criterio di successo 3.2.4 Identificazione coerente</h4>
     <p>I componenti che hanno la stessa funzionalità all'interno di un insieme di pagine Web sono identificati in modo coerente.</p>
     <br>
     <p><strong>Esito: POSITIVO</strong></p>
</div>


### Linea guida 3.3 Assistenza nell'inserimento

Aiutare gli utenti a evitare gli errori e agevolarli nella loro correzione.


<div class="success-criteria">
     <h4>Criterio di successo 3.3.3 Suggerimenti per gli errori</h4>

     <p>Se viene identificato un errore di inserimento e sono noti dei suggerimenti per correggerlo, tali suggerimenti vengono forniti all'utente, a meno che ciò non pregiudichi la sicurezza o la finalità del contenuto.</p>
</div>

<div class="success-criteria success-criteria-warning">
     <h4>Criterio di successo 3.3.4 Prevenzione degli errori (legali, finanziari, dati)</h4>
     <p>Per le pagine Web che contengono vincoli di tipo giuridico o transazioni finanziarie per l'utente che gestiscono la modifica o la cancellazione e gestione di dati controllabili dall'utente in un sistema di archiviazione oppure che inoltrano le risposte degli utenti a test, è soddisfatta almeno una delle seguenti condizioni: reversibilità, controllo, conferma.</p>
     <br>
     <p><strong>Esito: NON VALUTABILE</strong></p>
</div>

## 4. Robusto

Il contenuto deve essere abbastanza robusto per essere interpretato in maniera affidabile da una grande varietà di programmi utente, comprese le tecnologie assistive.

### Linea guida 4.1 Compatibile

Garantire la massima compatibilità con i programmi utente attuali e futuri, comprese le tecnologie assistive.

<div class="success-criteria">
     <h4>Criterio di successo 4.1.3 Messaggi di stato</h4>
     <p>Nei contenuti implementati utilizzando i linguaggi di marcatura, i messaggi di stato possono essere determinati programmaticamente tramite ruolo o proprietà in modo tale che possano essere presentati all'utente mediante tecnologie assistive senza ricevere il focus.</p>
     <br>
     <p><strong>Esito: </strong></p>
</div>
