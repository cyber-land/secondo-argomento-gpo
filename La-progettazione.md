# La progettazione (0(1))

Nel rapporto tra tempi, risorse e costi, la condizione di **trade-off** è una decisione in cui la perdita di valore di uno costituisce un incremento di valore di un altro.

### Progetto e project management (2(4))

The **PMBOK** (Project Management Body Of Knowledge) is a set of standard terminology and guidelines for project management.

Il **progetto** ha uno scopo ben definito (unicità), ha un inizio ed una fine (temporaneo) ed ha dei vincoli da rispettare e dei rischi da valutare (trade-off).

il **project manager** è il resonsabile di un progetto

I **processi** descrivono le tecniche e le metodologie per gestire le varie attività connesse alla progettazione, cosicché si può aggiungere che un progetto è anche:

- organizzato in processi

- i processi sono composti da fasi interconnesse

i risultati parziali che ogni fase produce sono detti **deliverables**

Le **milestones** sono eventi importanti de progetto, anche associati ai deliverable

Tutte le figure coinvolte nell'attività sono detti **stakeholders**

Ciclo di vita:

- Avvio

- Esecuzione

- Chiusura

Divisione dei processi in 5 gruppi fondamentali:

- Avvio (Initialing)

- Pianificazione (Planning)

- Esecuzione (Executing)

- Monitoraggio e controllo (Monitoring and control)

- Chiusura (Closing)

Le 9 aree(/fasi) di conoscenza sono le seguenti:

- Integrazione: tutti i processi necessari per coordinare le varie attività di gestione del progetto

- Scopo: riguarda tutti quei processi necessari per assicurare che venga preso  in considerazione tutto il lavoro necessario per completare il lavoro.

- Tempi (Project Time Management), i processi necessari per assicurare il
  completamento temporale del progetto.

- Costi (Project Cost Management), i processi necessari per definire la di-
  sponibilità finanziaria (budget) del progetto e assicurare che venga ri-
  spettato.

- Rischi (Project Risk Management), tutti i processi necessari per assicura-
  re l’identificazione e la risposta ai rischi di progetto.

- Qualità (Project Quality Management), processi necessari per assicurare
  che gli obiettivi siano raggiunti con un determinato grado di qualità.

- Risorse Umane (Project Human Resources Management), processi ne-
  cessari per assicurare la corretta organizzazione e gestione del personale
  coinvolto nel progetto.

- Comunicazioni (Project Communications Management), processi ne-
  cessari per assicurare la corretta creazione e distribuzione delle infor-
  mazioni relative al progetto.

- Acquisti (Project Procurament Management), tutti i processi necessari per
  assicurare l’acquisizione dall’esterno di beni e servizi necessari al progetto.

La scomposizione gerarchica delle fasi del progetto è detta **Work Breakdown Structure** (WBS)

Il **diagramma reticolare di precedenza** (PDM, Precedence Diagramming Method) riporta le interconnessioni tra le fasi (processo di Pianificazione/Tempi)

Il **diagramma di Gantt** serve per organizzare e visualizzare la sequenza temporale delle fasi

### PMBOK (6(3))

Il complesso di tutti i processi di Project Management descritti nel PMBOK si può ricavare intersecando i 5 gruppi di processo con le 9 aree di conoscenza, ottenendo una tabella che riporta tutti i 42 processi previsti

(tabella con aree di conoscenza come righe e gruppi di processo come colonne)

Una matrice delle responsabilità (RACI o RAM) può costituire l'output di un processo (Esecuzione/Risorse umane)

Il **project character** è un documento stilato in fase di Avvio/Integrazione delinea le caratteristiche di base dell'intero progetto (obbiettivi, principali deliverables, milestones, vincoli e dipendenze, tempistica preliminare, principlali risorse, ...)

il **piano di progetto/project managment** è un documento sempre in evoluzione durante le fasi, rappresenta la principla fonte di informazioni sulla modalità di pianificazione, esecuzione, monitoraggio e controllo ed infine la chiusura del progetto.

Il **work package** è la documentazione delle attività che compaiono al livello più basso del WBS.

Un'attività di progetto significativa si conclude con un deliverable, il quale può essere composto e descritto da uno o più work package che ne costituiscono la lavorazione.

### WBS (9(4))

è la rappresentazione in forma grafica della composizione gerarchica di tutte le attività di un progetto.

Essa parte da livello più alto e riporta la scomposizione "ad albero" delle attività, disgregantole in unità via via più dettagliate fino a raggiungere il cosidetto *work package*  che è la lavorazione minima a cui può essere attribuito un responabile ed una durata.

Regola del 100%: la somma del lavoro dei "figli" deve essere uguale a quella del "padre"

Una volta stabilita la WBS si può cominciare a organizzare le risorse umane stabilite nel documento preliminare (il Project Charter).

a questo scopo si realizza la struttura di scomposizione dell’organizzazione del progetto si chiama **Organization Breakdown Structure** (OBS) e, dall’incrocio con la WBS, determina la matrice delle responsabilità di progetto (RAM o RACI).

Un Work Package normalmente riporta:

- il nome, il titolo e l’identificativo del Work Package, quindi la descrizio-
  ne del lavoro da svolgere (task);

- le date di inizio e completamento del lavoro;

- la responsabilità;

- gli input necessari per effettuare il lavoro;

- la descrizione dei risultati attesi ed eventuali milestone;

- le risorse necessarie;

- il livello di qualità e il dettaglio delle prestazioni;

- gli output del lavoro (deliverable);

- il budget assegnato.

# Capisaldi del progetto

### Tempi (13(8))

Una volta compilata la WBS ed estratta la lista delle attività, si inizia a schedulare nel tempo il progetto, ovvero a organizzarlo secondo le previsioni e i vincoli temporali che ogni attività comporta (Pianificazione/Tempi, “Sviluppare la schedulazione”).
Il primo passo è individuare un modello di schedulazione da adottare; uno dei modelli più diffusi prende il nome di **CPM (Critical Path Method)**.
Si tratta di un modello di tipo reticolare che si basa sulla teoria dei grafi, i **nodi** del grafo rappresentano le attività e gli **archi** orientati le dipendenze tra le attività
Il grafo deve avere un solo nodo iniziale (l’avvio del progetto) e un solo nodo finale (la chiusura del progetto).

Le dipendenze tra le attività in un grafo di tipo CPM prevedono una delle seguenti modalità tipiche (una in serie, le altre in parallelo):

- FS, (Finish to Start, in serie): l’attività attuale può iniziare solo se quella precedente è terminata (“gettare la pasta” -  “far bollire l’acqua”)

- SS, (Start to Start, in parallelo): l’attività attuale può iniziare solo se quella precedente è a sua volta già iniziata (“collaudo” - “produzione”)

- FF, (Finish to Finish, in parallelo): l’attività attuale può terminare solo se quella precedente è a sua volta già terminata

- SF, (Start to Finish, in parallelo): l’attività attuale può terminare solo se quella precedente è già iniziata.

La schedulazione con CPM consente di calcolare la durata totale di un progetto e permette di valutare le attività critiche, cioè quelle attività per le quali un ritardo implica il ritardo dell’intero progetto.

*l’analisi “al più presto”*

Una volta stabilita la data iniziale del progetto (data del primo nodo), la determinazione delle date di inizio attività e fine attività “al più presto” avviene a partire dalla data del nodo iniziale, supposto a durata zero; quindi, a partire da questa e seguendo gli archi:

- la data iniziale di un’attività si calcola dalla data finale del nodo predecessore (un giorno dopo quella), se un’attività ha più di un predecessore, come data iniziale si considera la maggiore delle date finali dei suoi predecessori.

- la data finale di un’attività si calcola dalla sua data iniziale più la sua durata;

*l’analisi “al più tardi”*

Per ogni fase i passi sono molto simili a quelli visti in precedenza, ma vanno effettuati a ritroso, a partire dalla data finale e calcolando per prima la data finale di ogni attività:

- la data finale di un’attività si calcola a partire dalla data iniziale del suo
  successore (questa volta un giorno prima di quella), se un’attività ha più di un successore, come data finale si considera la minore delle date iniziali dei suoi successori.

- la data iniziale dell’attività si calcola dalla sua data finale meno la sua
  durata;

Un'attività è **critica** quando la data finale “al più tardi” corrisponde alla data finale
“al più presto” (la sottrazione tra le due si chiama **scorrimento**)

La durata di un’attività non critica può essere aumentata senza compromettere la schedulazione del progetto fino a un massimo pari al suo scorrimento

Un altro strumento molto efficace per rappresentare l’evoluzione temporale di un progetto è il **diagramma di Gantt**

In un diagramma di Gantt ogni attività è rappresentata con una barra orizzontale di larghezza proporzionale alla sua durata, mentre sulle colonne si rappresentano i giorni (o le settimane o i mesi o le ore, dipende dall’unità di tempo utilizzata) del calendario secondo la durata del progetto.
Le attività possono susseguirsi in sequenza oppure essere eseguite in parallelo e le barre del cronogramma risulteranno rispettivamente giustapposte o sovrapposte.
In particolare, con un diagramma di Gantt vengono messi in evidenza i possibili scorrimenti delle attività non critiche.

### Risorse (21(1))

La **pianificazione delle risorse** è di difficile standardizzazione, si tratta di un processo (Pianificazione/Tempi “Stimare le risorse”) che per sua natura deve essere reiterato più volte durante la vita del progetto e si basa sostanzialmente su analisi di stima.
In pratica si tratta di definire il tipo, le quantità di materiali, le persone, le attrezzature e le forniture necessarie per eseguire ciascuna attività prevista dal progetto.
Riferendosi alla WBS, si tratta di stimare le risorse che devono essere impiegate per produrre i deliverable previsti dal progetto e per completare i singoli Work Package.
Alla fine di questo processo si otterrà la lista delle risorse e il loro utilizzo in termini di unità di impiego (per esempio: ore/uomo, ore/macchina, quantità di materiale, ecc.), riportate in un documento denominato Requirement Breakdown Structure (RBS), ovvero una WBS che riporta la stima delle risorse.

### Costi (22(3))

Il risultato dell’analisi pianificata dei costi di un progetto è detto **budget di progetto**, ovvero la previsione di spesa del progetto.

I processi relativi alla pianificazione e di controllo dei costi (Pianificazione/Costi e Controllo/Costi) sono di gran lunga i processi su cui il Project Manager deve operare con attenzione e dei quali ha quasi sempre la completa responsabilità.

Il controllo periodico dei costi (**timenow**) consentirà di valutare l’andamento complessivo del progetto e suggerirà le strategie per migliorarlo in caso di scostamenti dal budget di progetto preventivato.

I **costi** vengono classificati in:

- diretti, specifici per la realizzazione del progetto

- indiretti, solo funzionali alla realizzazione del progetto

I costi diretti di un progetto invece si possono valutare soltanto dopo averne precisato lo scopo, per esempio attraverso la compilazione della WBS.

In generale la stima di costo più impegnativa di un progetto riguarda la stima dei costi diretti, ovvero dei costi specifici che ogni attività prevista dal progetto comporta.