# honestAG su GitHub Pages

## Pubblicazione
1. Crea un repository pubblico su GitHub.
2. Carica `index.html` e `.nojekyll` nella cartella principale del repository.
3. Apri **Settings → Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**, seleziona `main` e la cartella `/ (root)`, quindi salva.
5. Attendi la pubblicazione: GitHub mostrerà l’indirizzo del sito nella pagina Pages.

## Chatbot
Il sito invia i messaggi a `/api/chat`, ma il codice del backend non è incluso in questo pacchetto. La pagina si pubblica, ma il chatbot non risponderà finché non viene configurato un servizio backend.