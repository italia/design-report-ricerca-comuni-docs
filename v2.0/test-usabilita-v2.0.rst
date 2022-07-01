Test di usabilità
=====================

A seguito della valutazione euristica, sono stati condotti test di usabilità con utenti, finalizzati a validare il modello Comuni e a valutare:

- il processo per richiedere un servizio, dalla sua individuazione all’accesso al tool specifico;
- se l’utente riuscisse ad individuare le informazioni necessarie per godere di un servizio offerto dal Comune;
- l’efficacia dell’architettura dell'informazione.


I test hanno coinvolto 8 persone residenti nel territorio italiano, di cui 6 maschi e 2 femmine in un range di età fra i 23 e i 66 anni. La tecnica di selezione dei partecipanti ha garantito la presenza di ambo i sessi e di un ampio spettro di età.

.. list-table:: Partecipanti ai test di usabilità.
   :widths: 30 30 30 30
   :header-rows: 1

   * - Compito
     - Utenti che hanno superato il test
     - Utenti che hanno superato il test con difficoltà
     - Utenti che non hanno superato il test
     
   * - 1. Richiedere l’assegno di maternità
     - 4
     - 3
     - 1
   
   * - 2. Richiedere un permesso ZTL alunni
     - 3
     - 3
     - 2
     
   * - 3. Individuare la biblioteca comunale
     - 4
     - 3
     - 1
    
   * - 4. Prenotare un appuntamento presso l'ufficio del Comune 
     - 3
     - 3
     - 2
   
   * - 5. Richiedere il servizio scuolabus
     - 5
     - 2
     - 1
     
Alla fine del test, è stato chiesto ai partecipanti di rispondere a un questionario di 2 domande, su scala Likert 1-5:

- le caratteristiche del sito web incontrano le tue necessità?
- questo sito web è facile da usare?

Una sola persona ha dato un punteggio inferiore a 4 in una delle due domande.


Dal test sono emersi 3 problemi critici (che possono portare l'utente a non completare il task), 3 problemi seri (che possono avere un impatto negativo sul completamento del task) e 2 problemi minori.

**Problemi critici**

- L'architettura dell'informazione della sezione servizi è confusionaria per gli utenti.
- L’accesso all’area personale non è intuitivo.
- L’impossibilità di poter prenotare un appuntamento direttamente dalle schede servizio, soprattutto per i servizi non richiedibili online.

**Problemi seri**

- Nei monitor di piccole dimensioni, alcuni utenti non capivano che vi erano contenuti sotto al "fold".
- I risultati del motore di ricerca sono ordinati per data e non per pertinenza, risultando spesso poco utili.
- Alcuni servizi hanno una collocazione ambigua. Se l'utente non indovina la categoria, diventa difficile trovarli.

**Problemi minori**

- L'etichetta "Documenti e dati" per alcuni utenti rappresenta i documenti e i dati personali. 
- Alcuni link nelle schede servizio non funzionavano.


I risultati emersi della ricerca sono poi stati categorizzati per tipologia di criticità e organizzati per priorità.

**Architettura dell’informazione**

- Ricerca e filtri nelle pagine di secondo livello: la modalità di funzionamento del motore di ricerca presente nelle "pagine lista" di primo livello ("Amministrazione", "Servizi", "Novità", "Documenti e dati") risulta difficile da capire, soprattutto per quanto riguarda i filtri.
- Tassonomie piatte e lunghe liste: alcune categorie presentano una lista di elementi molto lunga, in ordine alfabetico e paginata. Questo costringe a scorrere pagine e pagine di elementi, rendendo problematica la trovabilità.
- Accesso ai form di richiesta del servizio: ad alcuni partecipanti non è chiaro che “Accedi all’area personale” è la voce in alto a destra, anche perché sugli schermi di piccole dimensioni la voce è nascosta. Inoltre, nella versione mobile è presente soltanto l’icona. Questo problema è critico perché può risultare bloccante se l’utente non comprende come accedere all’area.
- Prenotazione appuntamento: c’è chi cerca un servizio specifico per la ricerca di un appuntamento, chi cerca l’ufficio presso il quale richiedere l’appuntamento, mentre molti cercano prima il servizio e poi si aspettano di poter richiedere un appuntamento direttamente dalla scheda servizio. 
- Struttura delle schede servizio: dalle analisi è apparso che le pagine "foglia" (relative ai contenuti veri e propri) sono sostanzialmente ben strutturate. Ciononostante, le pagine di descrizione dei servizi (le "Schede servizio") sono spesso molto ricche di contenuti non strutturati, e alcune informazioni importanti non sono immediate da trovare.
- Trovabilità di servizi dalla collocazione ambigua: uno dei compiti del test era di trovare il servizio Scuolabus. Alcuni partecipanti cercano la voce nella categoria “Mobilità e Trasporti”, altri in “Educazione e Formazione”. Questo tipo di problemi emerge per tutte le voci la cui categorizzazione, dal punto di vista dell’utente, è ambigua.

**Motore di ricerca**

- I risultati sono ordinati per data (o alfabeticamente): non conoscendo il nome esatto o la data di pubblicazione del servizio o contenuto che cercano l'ordinamento alfabetico o per data non risulta essere d’aiuto agli utenti che spesso non riescono a trovare ciò che li interessa, andando per tentativi successivi fino a quando il contenuto non viene presentato tra i primi risultati. Questo tipo di ordinamento non mette in evidenza i risultati più rilevanti per una specifica ricerca.
- Non è possibile modificare la stringa di ricerca: non è possibile raffinare la pagina dei risultati di ricerca: questo obbliga l’utente a procedere con una nuova ricerca partendo da zero.

**Aspetti cognitivi**

- Percezione della lunghezza della pagina: alcuni partecipanti ai test che hanno usato computer con monitor piccoli non notano che vi sono contenuti sotto alla sezione che contiene il titolo di pagina e la sua descrizione, e dunque non scorrono la pagina per visualizzarli. Inoltre la modalità di caricamento della pagina (prima header e footer, poi contenuti) trae in inganno gli utenti con connessione più lenta, che per alcuni secondi visualizzano una pagina priva di contenuti.
- Rappresentazione delle card delle categorie: attualmente, nel modello (e nell'implementazione del comune testato) le card che rappresentano le pagine "foglia" (il servizio, la persona, il luogo) e quelle che rappresentano le categorie ("Anagrafe e stato civile", "Politici", "Edifici di culto") utilizzano la stessa interfaccia, generando ambiguità. 
- Ambiguità dell'etichetta "Documenti e dati": per minimizzare il rischio che le persone interpretassero la sezione "Documenti e dati" come l'area personale erano state proposte alcune soluzioni che in seguito sono state superate con la revisione dell'architettura dell'informazione, dove "Documenti e dati" è diventata una voce di secondo livello di "Amministrazione".


  
