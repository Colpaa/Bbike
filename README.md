
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

1.Bbike                        100
1.1 Grafica                    25

1.2 Marketing                    

1.2.1 Social media             20 

1.2.2 TV marketing             10 

1.3 Integrazione 

1.3.1 Ideazione                8

1.3.2 Progettazione            12

1.3.3 Commercializzazione      15

1.4 Gestione Progetto          10

