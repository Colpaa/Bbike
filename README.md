# Bbike
Scarica, scannerizza e pedala! Bbike, la nuova applicazione che permette di girare in bici tutta Bergamo.

La mia applicazione si basa sul modello dell'applicazione BiGi.
Il problema che risolvo è quello del trasporto veloce nella città di Bergamo. Quante volte infatti ci siamo trovati in una situazione nella quale per esempio dovevamo raggiongere la fermata del pullman che era a 20 min a piedi. 
E proprio in quella situazione ci trovavamo a desiderare un metodo più veloce per raggiungere la nostra destinazione.
Ed è proprio in quella situazione che la nostra applicazione viene in aiuto! Con la numerosa quantità di bicilette che intendiamo mettere a disposizione potrai trovarne una nelle vicinanze ovunque ti trovi! 
E in quel momento ti basta scannerizzarle il codice QR posizionato sul manubrio della bicicletta e pedalare comodamente fino alla destinazione. 

Requisiti applicazione

Registrazione:

    -Ogni utente deve prima effettuare la registrazione prima di effettuare ogni tipo di noleggio.
    -Questa operazione comprende anche l' autenticazione

Noleggio:

    -L'applicazione deve permettere all'utente di noleggiare le biciclette.
    -Oltre a far partire l'opzione noleggio l'applicazione deve anche essere in grado di farlo terminare

Prenotazione:

    -Un utente può anche decidere di effettuare una prenotazione su un mezzo, escludendo il noleggio del mezzo prenotato ad altri utenti.
    -Questa opzione avrà una durata differente in base all' abbonamento scelto dall'utente.
    -In caso che l'utente non abbia nessun abbonamento la durata della prenotazione sarà stabilita a 15 minuti.

Parcheggio:

    -Il comando termina noleggio dovrà essere per forza eseguito in spazi apposta allestiti a parcheggi.
    -Questi spazi potranno essere visualizzati semplicemente nella mappa.
    -Ci sarà pure l'opzione naviga verso parcheggio, che calcolerà il percorso più veloce verso il parcheggio più vicino.

Pagamento:

    -Alla fine del noleggio l'utente dovrà effettuare il pagamento.
    -Questa operazione verrà a meno in caso di un precedente acquisto di un abbonamento.

Scelta abbonamento:

    -L'utente potrà effettuare l'acquisto di vari abbonamenti, in base alle sue esigenze.
    -Abbonamento 3 mesi: dovrai pagare una quota fissa, e dopo di che potrai viaggiare per quanto vuoi senza preoccuparti dei prezzi per i prossimi 3 mesi.
    -Abbonamento 6 mesi: dovrai pagare una quota fissa, e dopo di che potrai viaggiare per quanto vuoi senza preoccuparti dei prezzi per i prossimi 6 mesi.
    -Abbonamento 1 anno: dovrai pagare una quota fissa, e dopo di che potrai viaggiare per quanto vuoi senza preoccuparti dei prezzi per il prossimo anno.

Sicurezza:

  -Ovviamente l'applicazione dovrà prevedere un software di sicurezza per prevenire il furto dei mezzi.

Manutenzione:

    -Ogni bicicletta sarà compresa di un chip, che ne dirà lo stato.
    -In caso di stato del mezzo compromesso la bici verra portata in manutenzione, per poi essere rimessa a disposizione dei clienti

Naviga:

    -Nella home dell'applicazione ci sarà una mappa digitale.
    -Si sceglierà quindi una destinazione, e la mappa mostrerà il percorso più veloce per arrivarci.

MultiNoleggio:

    -Un utente avrà anche la possibilità di noleggiare più biciclette contemporaneamente.
    -Ad ogni bicicletta noleggiata in più corrisponderà una sconto sempre più alto.
    -Ci sarà un numero massimo di biciclette da noleggiare contemporaneamente, che sarà di 5.



Di seguito espongo il diagramma UML del CLIENTE
<img src="http://yuml.me/diagram/scruffy/usecase/[Cliente]-(Registrazione),[Cliente]-(Noleggio mezzo),(Noleggio mezzo)>(Autenticazione),[Cliente]-(Prenotazione mezzo),(Prenotazione mezzo)>(Noleggio mezzo),(Prenotazione mezzo)>(Autenticazione),(Registrazione)<(Acquisto abbonamento),(Acquisto abbonamento)>(Aggiungi carta),(Acquisto abbonamento)>(Autenticazione)" >



Il diagramma UML del SISTEMA invece è questo
<img src="http://yuml.me/diagram/scruffy/usecase/[Sistema]-(Attivazione mezzo),(Attivazione mezzo)>(mezzo sbloccato),[Sistema]-(Parcheggio mezzo),(Parcheggio mezzo)>(Posto parcheggio disponibile),[Sistema]-(Controllo stato mezzo)" >
