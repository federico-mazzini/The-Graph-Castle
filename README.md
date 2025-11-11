# The Graph Castle

**The Graph Castle** è un gioco interattivo sviluppato in **HTML**, **CSS** e **JavaScript** per esplorare i concetti di **grafi**, **nodi** e **algoritmi di visita** (BFS e DFS) attraverso una storia ambientata in un misterioso castello.

## Obiettivo del progetto

Il progetto nasce come risorsa didattica per introdurre gli studenti allo studio dei **grafi** in modo coinvolgente e narrativo.  
Ogni stanza del castello rappresenta un **nodo**, e i collegamenti tra le stanze rappresentano gli **archi** del grafo.  
Durante il gioco, il giocatore esplora le stanze, scoprendo segreti e collegamenti nascosti, costruendo progressivamente la **mappa magica** — una rappresentazione grafica del grafo visitato.

## Concetti didattici

- Struttura dati **grafo**  
- Concetto di **nodo (stanza)** e **arco (passaggio)**  
- **Visita in profondità (DFS)** e **visita in ampiezza (BFS)**  
- Rappresentazione visiva della **mappa dei percorsi**  
- Introduzione all’idea di **cammino minimo** (numero di stanze attraversate)

## Trama del gioco

Il saggio **Edsger** deve trovare una **fessura nel muro** del castello, unico punto in cui può arrivare un messaggio segreto inviato da un piccione viaggiatore.  
Di giorno può muoversi liberamente, ma di notte deve attraversare il minor numero possibile di stanze per non farsi scoprire dalle guardie.  
Ogni stanza nasconde oggetti o indizi che aiutano a ricostruire la verità sul regno e sul misterioso segreto della corona.

## Funzionalità principali

- Navigazione tra stanze (Nord, Sud, Est, Ovest)
- Descrizione dinamica dell’ambiente corrente
- “Mappa magica” che si aggiorna in tempo reale mostrando nodi e collegamenti visitati
- Contatore dei passi e del cammino compiuto
- Popup e interazioni (es. scoperta della fessura o oggetti nascosti)
- Accessibilità e interfaccia responsive
- Modalità “notturna” per la fase stealth del gioco

## Struttura del progetto

```
code/
 ├── index.html        # Struttura principale del gioco
 ├── style.css         # Stile e layout delle stanze e dell’interfaccia
 ├── script.js         # Logica del gioco e gestione della mappa
 ├── assets/           # Immagini, icone e risorse grafiche
 └── README.md         # Documentazione del progetto
```

## Installazione e uso

Puoi eseguirlo direttamente in locale:
1. Clona la repository
   ```bash
   git clone https://github.com/fedemazzini/graph-castle.git
   cd graph-castle
   ```
2. Apri `index.html` con un browser

Oppure esploralo online tramite GitHub Pages:
https://fedemazzini.github.io/graph-castle/

## Obiettivi futuri

- Implementare la visualizzazione animata degli algoritmi di visita (DFS/BFS)
- Aggiungere modalità “sfida” per risolvere enigmi basati sui percorsi
- Integrare suoni ambientali e narrazione audio
- Creare un livello editor per disegnare nuovi castelli

## Autore

Progetto sviluppato da **Federico Mazzini**, docente di informatica e ingegnere informatico, nell’ambito del percorso abilitante per l’insegnamento (PF60 – Università di Bologna).  
Il gioco nasce come strumento didattico per avvicinare gli studenti alla logica dei grafi attraverso il gioco e la narrazione.