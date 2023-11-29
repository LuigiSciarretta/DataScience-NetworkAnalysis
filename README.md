# DataScience-NetworkAnalysis
Facebook Graph Analysis

Il progetto è realtivo ad uno dei 4 progetti del corso di Data Science presso l'Università Politecnica delle Marche.
L'obiettivo è stata l'applicazione delle tecniche di Graph Analysis e Graph Thoery utilizzando la libreria Networkx di Python, espandendo le compteneza relativa all'ecosistema di librerie per la Data Science. 

Per il progetto, si è scelto un dataset di pagine Facebook, accessibile al link: 
https://snap.stanford.edu/data/facebook-large-page-page-network.html

La rete esaminata nel progetto è una collezione di pagine Facebook verificate, ottenuta attraverso la Facebook Graph API nel novembre 2017 e limitata a quattro categorie principali: politici, organizzazioni governative, spettacoli televisivi e aziende. Questa rete è modellata come un grafo, in cui i nodi rappresentano le pagine Facebook e i collegamenti tra i nodi sono rappresentati dai reciproci "like" tra le pagine.
Le analisi condotte riguardano il calcolo di diverse misure di centralità per comprendere quali pagine occupino una posizione rilevante all'interno della rete. Inoltre, sono state eseguite analisi relative alla rilevazione delle comunità nella rete, con la conseguente visualizzazione grafica all'interno del grafo. Utilizzando la Cliques Detection, è stata individuata la cricca massima della rete, e attraverso la creazione di una Ego Network, la rete è stata centrata sulla pagina con il maggior numero di connessioni.
Le varie misure di centralità sono state ricalcolate considerando non solo le pagine singolarmente, ma anche i quattro gruppi distinti di pagine Facebook. Infine, è stato implementato un algoritmo di Classificazione Multinodo per predire il tipo di pagina basandosi sulle caratteristiche dei nodi.

Il file "project-documentation" è una tesina del progetto, in cui sono racchiusi i dettagli delle analisi.
