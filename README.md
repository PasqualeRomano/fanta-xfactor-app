# Fanta X Factor

Web app per giocare al fanta X Factor tra amici: draft delle squadre, X Pass di Giorgia, pronostici sulle puntate, griglia punteggi e classifica live.

È un sito statico (GitHub Pages). La partita condivisa è salvata su Firebase Firestore.

## Configurazione

1. Crea un progetto su [Firebase](https://console.firebase.google.com), poi crea il database Firestore.
2. Nella scheda **Regole** di Firestore incolla il contenuto di `firestore.rules` e pubblica.
3. Aggiungi un'app **Web** al progetto e copia i valori di `firebaseConfig` in `config.js`.

Se `config.js` resta vuoto, l'app funziona lo stesso, ma salva i dati solo sul dispositivo.

## Più partite

Aggiungi `?partita=nome` al link per avere partite separate (es. `.../?partita=amici-ufficio`).
