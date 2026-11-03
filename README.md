# Sport Hub Compensi

App web per caricare le presenze dei collaboratori sportivi di Sport Hub SSD Impresa Sociale, calcolare i compensi da bonificare e i contributi oltre i 5.000 €.

- Questo repository contiene **solo il codice della pagina**. Nessun dato.
- I dati sono nel database **Firebase Firestore** e sono leggibili solo dagli utenti creati dall'amministratore (accesso con email e password).
- La configurazione Firebase in `config.js` è pubblica per natura: la protezione è data dalle regole di Firestore (`firestore.rules`) e dalla registrazione autonoma disattivata.

Pagina pubblicata con GitHub Pages.
