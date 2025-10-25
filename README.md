
# German Verb Quiz (Vite + React)

Progetto Vite + React minimal per esercitarsi con i verbi tedeschi.
Contiene:
- 200 domande generate programmaticamente
- 5 opzioni a scelta multipla per domanda
- Comportamento predefinito: al primo errore si ricomincia
- Modalità vite (opzionale) che permette più errori prima del reset
- Statistiche salvate in localStorage (corrette, tentativi, streak, best)

## Come eseguire
1. Estrarre la cartella
2. Eseguire nella cartella del progetto:
```bash
npm install
npm run dev
```

Questo aprirà l'app su `http://localhost:5173` (porta di default).

## Note
- Il progetto è volutamente semplice e non richiede Tailwind.
- Puoi modificare il file `src/App.jsx` per cambiare il comportamento, aggiungere altre lingue o salvare le statistiche su server.
