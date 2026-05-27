# JARVIS OS - Demo Capolavoro

Questa cartella contiene una versione statica di JARVIS OS pensata per essere pubblicata su GitHub Pages come capolavoro scolastico.

La demo usa la stessa interfaccia principale del progetto originale, ma intercetta le API in JavaScript e mostra dati simulati. Non controlla il PC, non usa credenziali, non chiama Spotify reale, non scrive file e non richiede il backend Python.

## File

- `index.html` - interfaccia JARVIS originale in modalita demo, con mock API integrati.
- `README.md` - descrizione della demo e istruzioni di pubblicazione.

## Cosa mostra

- dashboard cyberpunk/tattica originale;
- core 3D centrale;
- terminale comandi;
- widget sistema, meteo, task, audio e orologio;
- widget Spotify demo con copertina/disco, minutaggio, volume e controlli simulati;
- widget Report News demo;
- risposte simulate per comandi testuali.

## Cosa non fa

Questa build e volutamente sicura:

- non apre app reali;
- non esegue comandi sul sistema;
- non usa Ollama;
- non usa Spotify OAuth;
- non legge o scrive file locali;
- non fa scraping reale;
- non contiene client secret o dati personali.

## Come provarla

Apri direttamente:

```text
index.html
```

Oppure pubblicala su GitHub Pages.

## Pubblicazione GitHub Pages

1. Crea un repository GitHub.
2. Carica il contenuto della cartella `capolavoro`.
3. Vai in `Settings > Pages`.
4. Scegli `Deploy from a branch`.
5. Seleziona branch `main` e cartella `/root`.
6. Salva e attendi il link pubblico.

Se pubblichi tutto il repository Jarvis, puoi invece impostare GitHub Pages sulla cartella `/capolavoro`, se disponibile.

## Descrizione breve per la presentazione

JARVIS OS e un prototipo di assistente AI locale pensato come interfaccia operativa personale. Il progetto mostra come un assistente non debba essere solo una chat, ma un sistema composto da router di intenti, tool controllati, widget, policy di sicurezza, memoria e task agentiche.

Questa versione demo presenta l'esperienza visiva e il flusso d'uso senza eseguire azioni reali, rendendola adatta alla pubblicazione pubblica e alla dimostrazione scolastica.
