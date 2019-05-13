# FFP

Facebook Frame Publisher: upload all the frame of a video to Facebook with a bot

***

### How to download

`git clone https://github.com/GarageLabsCorps/ffp`

### How to use

`python ffp`

or

`./ffp`

### How to make a Facebook bot

Per fare un bot Facebook recati all'indirizzo "https://developers.facebook.com/". Clicca in alto a destra dove c'è scritto "Le mie app" e clicca su "Aggiungi nuova app". Dopo aver scelto il nome e l'email di contatto clicca sul pulsante blu "Crea ID app". Una volta verificato il captcha ti uscirà una schermata con su scritto "Seleziona uno scenario". Spunta tutti gli scenari disponibili e clicca su "conferma".
### How to get the token

Adesso recati al sito "https://developers.facebook.com/tools/explorer" e dove c'è scritto "App" in alto a destra assicurati che appaia affianco il nome dell'app da te appena creata. Adesso clicca sotto su "Ricevi token" e clicca su "Ricevi token d'accesso alla Pagina". Si aprirà una finestra di Facebook che ti chiederà di continuare con il tuo profilo. Scegli di continuare. Seleziona tutte le pagine che intendi gestire, prosegui e lascia la leva a sì sull'unica voce che leggi "gestire le tue pagine". Una volta finito appariranno sotto al pulsante "Ricevi token" tutte le voci con le relative pagine Facebook che gestisci. Clicca sul nome della tua pagina che intendi utilizzare e vedrai a sinistra il suo token d'accesso.


### How to get the id
Una volta ottenuto il token d'accesso alla pagina, trovare l'ID è veramente semplice. Nella barra di sotto dove c'è scritto "GET" cancella tutto quello che c'è scritto dopo e scrivi solo "me". Premi invio e ti dovrebbe uscire nel riquadro sotto una cosa del genere:

{
  "name": "La tua pagina Facebook bellissima",
  "id": "415922862420666"
}

Ovviamente quella stringa di numeri è l'ID della tua pagina. D'altra parte, c'è scritto anche affianco.

***

[DEVELOPERS](https://github.com/GarageLabsCorps)

[LICENSE](LICENSE)
