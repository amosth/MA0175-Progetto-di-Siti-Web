---
title: Rapporto di test con utenti del sito "RAI Friuli Venezia Giulia" | Sommario dei Risultati
summary: Rapporto di test con utenti del sito "RAI Friuli Venezia Giulia" | Sommario dei Risultati.
authors:
    - Enrico Basso
    - Amos Cappellaro
    - Luca Dal Poz
date: 2019-07-10
---
# Valutazioni finali user test del sito Sede Rai FVG

## Tabella riassuntiva dei risultati

<table>
    <thead>
        <th>Caso d'uso</th>
        <th>Partecipante A</th>
        <th>Partecipante B</th>
        <th>Partecipante C</th>
        <th>Partecipante D</th>
        <th>Partecipante E</th>
    </thead>
    <tbody>
        <tr>
            <th scope="row">1</th>
            <td class="centred bg-danger">Negativo</td>
            <td class="centred bg-success">Positivo</td>
            <td class="centred bg-success">Positivo</td>
            <td class="centred bg-danger">Negativo</td>
            <td class="centred bg-success">Positivo</td>    
        </tr>
        <tr>
            <th scope="row">2</th>
            <td class="centred bg-danger">Negativo</td>
            <td class="centred bg-danger">Negativo</td>
            <td class="centred bg-success">Positivo</td>
            <td class="centred bg-danger">Negativo</td>
            <td class="centred bg-success">Positivo</td>    
        </tr>
        <tr>
            <th scope="row">3</th>
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
        </tr>
        <tr>
            <th scope="row">4</th>
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
        </tr>
        <tr>
            <th scope="row">5</th>
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
            <td class="centred bg-success">Positivo</td>    
        </tr>
    </tbody>
</table>

## Problemi riscontrati

<table>
    <thead>
        <tr>
            <th scope="col">Caso d'uso</th>
            <th scope="col">Problema</th>
            <th scope="col">Gravità</th>
            <th scope="col">Possibile rimedio</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Tutti</td>
            <td>L'utente percepisce la prima navbar in alto dell'ente di appartenenza (in questo caso <a href="http://rai.tv">Rai</a>) come menu principale del sito in analisi e quindi basa principalmente la sua navigazione su questo elemento della pagina.</td>
            <td class="centred bg-warning">Minore</td>
            <td>Riconsiderare l'aspetto grafico della navbar per assegnarle il giusto significato.</td>
        </tr>
        <tr>
            <td>1-4-5</td>
            <td>Al momento dell'inserimento della query di ricerca nell'apposito form la scritta predefinita "Cerca nel sito" non scompare al focus dell'utente nell'input (perché impostata come <code>value</code> dell'input, non come placeholder). Questo causa errori di ricerca e perdita di tempo.</td>
            <td class="centred bg-warning">Minore</td>
            <td>Utilizzare un placeholder o meglio una label.</td>
        </tr>
        <tr>
            <td>4</td>
            <td>L'utilizzo della termine inglese "podcast" ha costituito una barriera nel raggiungimento dell'obiettivo per gli utenti che non conoscevano il significato di tale parola.</td>
            <td class="centred bg-warning">Minore</td>
            <td>Cambiare la dicitura "podcast" in "repliche" o simili.</td>
        </tr>
        <tr>
            <td>1-4-5</td>
            <td>Non è chiaro il funzionamento della ricerca all'interno del sito, i risultati non prevedibili dall'utente (la logica non si riesce nemmeno a indovinare).</td>
            <td class="centred bg-danger">Importante</td>
            <td>Riprogettare l'algoritmo di ricerca.</td>
        </tr>
    </tbody>
</table>
