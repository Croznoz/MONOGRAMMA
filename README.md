# Monogramma

Sito statico client-side per creare monogrammi geometrici ed esportarli in SVG o PNG. Non usa backend o database.

## Struttura

- `presentazione.html`: pagina principale, contenuti, FAQ e cambio lingua.
- `generatore.html`: editor del monogramma e download.
- `privacy-policy.html`: informativa bilingue.
- `logo.svg`, `og-image.svg`: identità visiva e anteprima social.
- `alfabetocircolare.png`, `alfabetoquadrato.png`: riferimenti geometrici.
- `index.html`: reindirizzamento alla presentazione.
- `vercel.json`, `robots.txt`, `sitemap.xml`: pubblicazione e indicizzazione.
- `ISTRUZIONI_MONOGRAMMA.md`: regole per modificare gli alfabeti.

## Sviluppo locale

Non serve una build. Per provare il sito con un server locale:

```bash
python3 -m http.server 8000
```

Apri `http://localhost:8000/` nel browser.

## Vercel

Il progetto viene pubblicato dalla cartella radice come sito statico. `vercel.json` abilita URL puliti e reindirizza `/` alla presentazione; le pagine principali sono `/presentazione`, `/generatore` e `/privacy-policy`.

## Pubblicità e privacy

Il generatore contiene il flusso di consenso e i punti di integrazione per banner e video rewarded. Prima di attivare annunci reali, inserire gli ID Google, completare i dati del titolare in `privacy-policy.html` e verificare fornitori, consenso e download.
