
# Bbike

<details>
<summary> Introduzione </summary>
Scarica, scannerizza e pedala! Bbike, la nuova applicazione che permette di girare in bici tutta Bergamo.
La mia applicazione si basa sul modello dell'applicazione BiGi. Il problema che risolvo è quello del trasporto veloce nella città di Bergamo. Quante volte infatti ci siamo trovati in una situazione nella quale, per esempio, dovevamo raggiungere la fermata del pullman che era a 20 minuti a piedi. Ed è proprio in quella situazione che desideriamo un metodo più veloce per raggiungere la nostra destinazione. Ed è proprio in quella situazione che la nostra applicazione viene in aiuto! Con la numerosa quantità di biciclette che intendiamo mettere a disposizione, potrai trovarne una nelle vicinanze ovunque ti trovi! E in quel momento ti basta scannerizzare il codice QR posizionato sul manubrio della bicicletta e pedalare comodamente fino alla destinazione.

<details>
<summary>Registrazione</summary>
Attori Principali: Utente<br>
  L'utente apre l'applicazione.<br>
  L'utente seleziona l'opzione di registrazione.<br>
  L'utente inserisce i dati richiesti (nome, email, password, ecc.).<br>
  L'applicazione verifica i dati e crea un account per l'utente.<br>
  L'utente viene autenticato automaticamente.<br>
Estensioni:<br>
 • Se i dati inseriti non sono validi, l'applicazione mostra un messaggio di errore.<br>
</details>
<details>
<summary>Noleggio</summary>
Attori Principali: Utente<br>
  L'utente è autenticato nell'applicazione.<br>
  L'utente apre la mappa dell'applicazione.<br>
  L'utente trova una bicicletta disponibile nelle vicinanze.<br>
  L'utente scannerizza il codice QR sulla bicicletta per iniziare il noleggio.<br>
  L'applicazione inizia a registrare il tempo del noleggio.<br>
  L'utente pedala verso la destinazione desiderata.<br>
  L'utente raggiunge la destinazione e termina il noleggio attraverso l'applicazione.<br>
  L'applicazione calcola il costo del noleggio e richiede il pagamento.<br>
Estensioni:<br>
 • Se la bicicletta non è disponibile, l'applicazione avvisa l'utente.<br>
 • Se l'utente supera il tempo massimo di noleggio senza restituire la bicicletta, verranno applicate tariffe aggiuntive.<br>
</details>
<details>
<summary>Prenotazione</summary>
Attori Principali: Utente<br>
  L'utente è autenticato nell'applicazione.<br>
  L'utente trova una bicicletta che desidera prenotare.<br>
  L'utente seleziona l'opzione di prenotazione per la bicicletta.<br>
  L'applicazione chiede la durata della prenotazione o usa il valore predefinito se l'utente non specifica una durata.<br>
  La bicicletta viene prenotata per l'utente per la durata specificata.<br>
  L'utente può poi ritirare la bicicletta nella durata della prenotazione.<br>
Estensioni:<br>
 • Se un'altra persona prenota la stessa bicicletta prima che l'utente vada a ritirarla, l'applicazione notifica l'utente e cancella la prenotazione.<br>
</details>
<details>
<summary>Pagamento</summary>
Attori Principali: Utente<br>
  L'utente ha terminato il noleggio di una bicicletta.<br>
  L'applicazione calcola il costo del noleggio in base al tempo trascorso.<br>
  L'applicazione richiede il pagamento all'utente.<br>
  L'utente inserisce i dettagli di pagamento (carta di credito, PayPal, ecc.).<br>
  L'applicazione elabora il pagamento e invia una ricevuta.<br>
Estensioni:<br>
 • Se il pagamento non riesce, l'applicazione avvisa l'utente e richiede un altro metodo di pagamento.<br>
</details>
<details>
<summary>Scelta Abbonamento</summary>
Attori Principali: Utente<br>
  L'utente è autenticato nell'applicazione.<br>
  L'utente accede alla sezione "Scelta Abbonamento."<br>
  L'utente seleziona uno tra i vari abbonamenti disponibili (3 mesi, 6 mesi, 1 anno).<br>
  L'applicazione calcola il costo dell'abbonamento.<br>
  L'utente conferma l'acquisto e effettua il pagamento.<br>
Estensioni:<br>
 • Se il pagamento dell'abbonamento non riesce, l'applicazione avvisa l'utente e richiede un altro metodo di pagamento.<br>
</details>
<details>
<summary>Sicurezza</summary>
Attori Principali: Sistema (Non funzionale)<br>
  L'applicazione implementa un software di sicurezza per prevenire il furto dei mezzi.<br>
  Il software monitora il movimento delle biciclette e rileva attività sospette.<br>
  In caso di furto o movimento non autorizzato, il sistema invia notifiche ai gestori dell'applicazione e agli utenti.<br>
Estensioni:<br>
 • Se viene rilevato un furto, il sistema attiva un sistema di tracciamento per recuperare la bicicletta.<br>
</details>
<details>
<summary>Manutenzione</summary>
Attori Principali: Operatore<br>
  Ogni bicicletta è compresa di un chip che ne monitora lo stato.<br>
  Il chip rileva eventuali problemi o danni alla bicicletta.<br>
  In caso di stato del mezzo compromesso, l'operatore viene notificato.<br>
  L'operatore recupera la bicicletta per la manutenzione e la ripara.<br>
  Dopo la manutenzione, la bicicletta viene rimessa a disposizione dei clienti.<br>
Estensioni:<br>
 • Se la bicicletta è troppo danneggiata per essere riparata, viene sostituita con una nuova bicicletta.<br>
</details>
<details>
<summary>Naviga</summary>
Attori Principali: Utente<br>
Nella home dell'applicazione, l'utente accede alla funzione "Naviga."<br>
L'utente seleziona una destinazione sulla mappa.<br>
  L'applicazione calcola il percorso più veloce per raggiungere la destinazione in bicicletta.<br>
  L'utente segue le indicazioni sulla mappa per guidarlo al suo scopo.<br>
Estensioni:<br>
 • Se ci sono problemi lungo il percorso (strade chiuse, lavori in corso, ecc.), l'applicazione calcola un percorso alternativo.<br>
</details>
<details>
  <summary>MultiNoleggio</summary>
Attori Principali: Utente<br>
  L'applicazione registra il noleggio della prima bicicletta.<br>
  L'utente ripete il processo per noleggiare una seconda bicicletta, e così via, fino a un massimo di 5 biciclette.<br>
  L'applicazione calcola sconti crescenti in base al numero di biciclette noleggiate contemporaneamente.<br>
  L'utente termina i noleggi delle biciclette quando ha finito di usarle.<br>
Estensioni:<br>
 • Se l'utente tenta di noleggiare più di 5 biciclette contemporaneamente, l'applicazione mostra un messaggio di errore.<br>
</details>
</details>



Di seguito espongo il diagramma UML del CLIENTE
<img src="http://yuml.me/diagram/scruffy/usecase/[Cliente]-(Registrazione),[Cliente]-(Noleggio mezzo),(Noleggio mezzo)>(Autenticazione),[Cliente]-(Prenotazione mezzo),(Prenotazione mezzo)>(Noleggio mezzo),(Prenotazione mezzo)>(Autenticazione),(Registrazione)<(Acquisto abbonamento),(Acquisto abbonamento)>(Aggiungi carta),(Acquisto abbonamento)>(Autenticazione)" >



Il diagramma UML del SISTEMA invece è questo
<img src="http://yuml.me/diagram/scruffy/usecase/[Sistema]-(Attivazione mezzo),(Attivazione mezzo)>(Sblocco mezzo),[Sistema]-(Parcheggio mezzo),(Parcheggio mezzo)>(Verifica Posto parcheggio),[Sistema]-(Controllo stato mezzo)" >


--- DIAGRAMMA WBS

1. Bbike 100<br>
   1.1 Analisi dei Requisiti  10 <br>
      1.1.1 Definizione dei Requisiti Utente 6<br>
      1.1.2 Analisi del Modello BiGi 4<br>
   1.2 Progettazione 15<br>
      1.2.1 Progettazione dell'Interfaccia Utente 10<br>
      1.2.2 Progettazione del Back-End 10<br>
   1.3 Implementazione 25 <br>
      1.3.1 Integrazione del Modello BiGi 3<br>
      1.3.2 Sviluppo della Funzionalità di Noleggio 3<br>
      1.3.3 Sviluppo della Funzionalità di Prenotazione 3<br>
      1.3.4 Sviluppo della Funzionalità di Pagamento 2<br>
      1.3.5 Sviluppo della Funzionalità di Scelta Abbonamento 3<br>
      1.3.6 Implementazione della Sicurezza 3<br>
      1.3.7 Implementazione della Funzionalità di Manutenzione 2<br> 
      1.3.8 Implementazione della Funzionalità di Navigazione 3<br>
      1.3.9 Implementazione della Funzionalità di MultiNoleggio 3<br>
   1.4 Test 35<br>
      1.4.1 Test di Unità 11<br>
      1.4.2 Test di Integrazione 12 <br>
      1.4.3 Test di Sistema 12<br>
   1.5 Commercializzazione 15 <br>
      1.5.1 Distribuzione dell'Applicazione 8<br>
      1.5.2 Configurazione dei Server 7<br>

--- SUDDIVISIONE DELLE USER STORIES

Sprint 1 (3 settimane - 40 ore di lavoro a settimana):

Registrazione:<br>

Come un utente voglio aprire l'applicazione in modo da poter accedere ai servizi offerti.<br>
Come un utente voglio selezionare l'opzione di registrazione in modo da creare un nuovo account.<br>
Come un utente voglio inserire i dati richiesti come nome, email e password in modo da completare il processo di registrazione.<br>
Come un utente voglio che l'applicazione verifichi i dati inseriti in modo da garantire la correttezza delle informazioni.<br>
Come un utente voglio essere autenticato automaticamente dopo la registrazione per accedere rapidamente all'applicazione.<br>
In caso di dati non validi, come un utente voglio che l'applicazione mostri un messaggio di errore per correggere eventuali errori.<br>

Sicurezza:<br>

Come un responsabile della sicurezza voglio che l'applicazione implementi un software di sicurezza per prevenire il furto delle biciclette.<br>
Come un responsabile della sicurezza voglio che il software monitori il movimento delle biciclette e rilevi attività sospette.<br>
In caso di furto o movimento non autorizzato, come un responsabile della sicurezza voglio che il sistema invii notifiche ai gestori dell'applicazione e agli utenti.<br>
In caso di furto, come un responsabile della sicurezza voglio che il sistema attivi un sistema di tracciamento per recuperare la bicicletta.<br>

Noleggio:<br>

Come un utente voglio essere autenticato nell'applicazione in modo da poter utilizzare i servizi di noleggio.<br>
Come un utente voglio aprire la mappa dell'applicazione per individuare una bicicletta disponibile nelle vicinanze.<br>
Come un utente voglio scannerizzare il codice QR sulla bicicletta per iniziare il noleggio.<br>
Come un utente voglio che l'applicazione registri il tempo del noleggio in modo da calcolare il costo corretto.<br>
Come un utente voglio pedalare verso la destinazione desiderata durante il noleggio.<br>
Come un utente voglio raggiungere la destinazione e terminare il noleggio attraverso l'applicazione.<br>
Come un utente voglio che l'applicazione calcoli automaticamente il costo del noleggio e richieda il pagamento.<br>
In caso di bicicletta non disponibile, come un utente voglio ricevere un avviso dall'applicazione.<br>
Come un utente voglio essere avvertito se supero il tempo massimo di noleggio e se vengono applicate tariffe aggiuntive.<br>

Prenotazione:<br>

Come un utente voglio essere autenticato nell'applicazione per prenotare una bicicletta.<br>
Come un utente voglio trovare una bicicletta che desidero prenotare sulla mappa.<br>
Come un utente voglio selezionare l'opzione di prenotazione e specificare la durata desiderata o accettare il valore predefinito.<br>
Come un utente voglio che l'applicazione prenoti la bicicletta per me per la durata specificata.<br>
Come un utente voglio poter ritirare la bicicletta durante la durata della prenotazione.<br>
Se un'altra persona prenota la stessa bicicletta prima che io la ritiri, come un utente voglio essere notificato e la prenotazione cancellata.<br>

Sprint 2 (3 settimane - 40 ore di lavoro a settimana):<br>

Pagamento:<br>

Come un utente voglio completare il noleggio di una bicicletta in modo che l'applicazione possa calcolare il costo in base al tempo trascorso.<br>
Come un utente voglio che l'applicazione richieda il pagamento e mi permetta di inserire i dettagli di pagamento.<br>
Come un utente voglio che l'applicazione elabori il pagamento e mi invii una ricevuta.<br>
In caso di pagamento non riuscito, come un utente voglio essere avvisato e poter utilizzare un altro metodo di pagamento.<br>

Scelta Abbonamento:<br>

Come un utente voglio essere autenticato nell'applicazione per accedere alla sezione "Scelta Abbonamento".<br>
Come un utente voglio poter selezionare uno tra vari abbonamenti disponibili, come abbonamenti di 3 mesi, 6 mesi o 1 anno.<br>
Come un utente voglio che l'applicazione calcoli il costo dell'abbonamento.<br>
Come un utente voglio confermare l'acquisto e effettuare il pagamento.<br>
In caso di pagamento dell'abbonamento non riuscito, come un utente voglio essere avvisato e poter utilizzare un altro metodo di pagamento.<br>

Manutenzione:<br>

Come uno sviluppatore voglio che ogni bicicletta sia dotata di un chip che monitori il suo stato.<br>
Come uno sviluppatore voglio che il chip rilevi eventuali problemi o danni alla bicicletta.<br>
In caso di stato compromesso del mezzo, come uno sviluppatore voglio essere notificato come operatore.<br>
Come uno sviluppatore voglio recuperare la bicicletta per la manutenzione e ripararla.<br>
Dopo la manutenzione, come uno sviluppatore voglio che la bicicletta sia nuovamente disponibile per i clienti.<br>
Se la bicicletta è troppo danneggiata per essere riparata, come uno sviluppatore voglio che venga sostituita con una nuova bicicletta.<br>

Naviga:<br>

Come un utente voglio poter accedere alla funzione "Naviga" dalla home dell'applicazione.<br>
Come un utente voglio selezionare una destinazione sulla mappa e che l'applicazione calcoli il percorso più veloce per raggiungerla in bicicletta.<br>
Come un utente voglio seguire le indicazioni sulla mappa per guidarmi alla destinazione.<br>
In caso di problemi lungo il percorso, come strade chiuse o lavori in corso, come un utente voglio che l'applicazione calcoli un percorso alternativo.<br>

MultiNoleggio:<br>

Come uno sviluppatore voglio che l'applicazione registri il noleggio della prima bicicletta.<br>
Come uno sviluppatore voglio poter ripetere il processo per noleggiare una seconda bicicletta, e così via, fino a un massimo di 5 biciclette contemporaneamente.<br>
Come uno sviluppatore voglio che l'applicazione calcoli sconti crescenti in base al numero di biciclette noleggiate contemporaneamente.<br>
Come uno sviluppatore voglio terminare i noleggi delle biciclette quando ho finito di usarle.<br>
Se tento di noleggiare più di 5 biciclette contemporaneamente, come uno sviluppatore voglio che l'applicazione mostri un messaggio di errore.<br>
