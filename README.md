# myBooking

Questo progetto nasce con lo scopo di replicare in piccola scala una applicazione web di tipo booking engine.

Il Booking Engine è un software che consente agli utenti che si collegano al sito web della struttura ricettiva di consultare comodamente, in tempo reale la disponibilità delle camere, le tariffe, e successivamente di prenotare in autonomia il soggiorno, fornendo, ad esempio i dati della propria carta di credito, a garanzia. In questo caso, per semplicità si è selezionato come target quello dei B&B.

## Tipologie di utenti:

|Utente non registrato|Utente registrato|Receptionist|Amministratore|
|---|---|---|---|
|Può registrarsi|Ha tutti i privilegi del non registrato|Carica le date disponibili|Ha il controllo totale|
|Può vedere disponibilità e offerta|Può fare la prenotazione|Carica l'offerta aggiornata||

- Utenti non registrati:
Possono effettuare la ricerca all'interno dell'applicazione, fornendo: date di arrivo e partenza, numero componenti adulti e bambini, numero camere.
Una volta fatta la ricerca possono vedere dettagli, prezzi ed eventuali sconti relativi alle camere corrispondenti. Possono registrarsi per ottenere le funzionalità deigli utenti registrati.

- Utenti registrati:
Hanno accesso a tutte le funzionalità degli utenti non registrati ed inoltre possono effeuare la prenotazione, selezionando un metodo di pagamento. Hanno la possibiltà di modificare o canellare la prenotazione in un determinato lasso di tempo.

### Funzionalità previste:
- Possibilità di caricare i dati della struttura ricettiva quali numero stanze, caratteristiche e foto di ognuna;

### Integrazione:
- Possibiltà di effettuare sconti ad esempio sette notti al prezzo di sei, oppure bimbo zero-due anni gratis.

###### Gruppo 3 (Programmazione Web DISIM UnivAQ)
