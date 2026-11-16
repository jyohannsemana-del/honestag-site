# HonestAG — sito pubblico

Questo repository contiene esclusivamente la pagina pubblica di HonestAG. La dashboard privata non è inclusa.

## Pubblicazione con Cloudflare Pages

Il sito è HTML statico. In Cloudflare Pages collega questo repository, lascia vuoto il comando di build e imposta la cartella di output su `.`. Cloudflare assegnerà un indirizzo `*.pages.dev`.

Dopo la pubblicazione, aggiungi l'indirizzo esatto `pages.dev` come segreto `PUBLIC_SITE_URL` nelle Edge Functions del progetto Supabase HonestAG. Così il sito potrà chiamare il chatbot.

## File pubblici

- `index.html` — pagina del sito.
- `chatbot-config.js` — URL della funzione chatbot; non contiene chiavi private.
