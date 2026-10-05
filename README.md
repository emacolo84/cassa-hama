# Quelli Sgranati

App per la cassa dei mercatini di Hama beads: vendite, incassi, refill, catalogo e spese.

- Si installa sull'iPhone da Safari: Condividi → Aggiungi alla schermata Home.
- Funziona anche senza rete; i dati si sincronizzano tra i telefoni tramite Firebase (Firestore + login email/password).
- `config.js` contiene la configurazione pubblica di Firebase. L'accesso ai dati è protetto dalle regole in `firestore.rules`.
- `vendor/` contiene l'SDK compat di Firebase 12.19.0 (licenza Apache 2.0).
- A ogni pubblicazione cambiare `VERSION` in `sw.js`.
