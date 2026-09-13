# Monogramma

Tool statico per generare monogrammi geometrici in SVG e PNG, senza backend.

## Pubblicità e download

La pagina include:

- un banner pubblicitario chiudibile dopo pochi secondi;
- un banner privacy con scelta tra annunci personalizzati e non personalizzati;
- un flusso video rewarded che abilita il download dopo la fine del video.

Il consenso viene salvato nel browser con `localStorage` e reso disponibile tramite `window.monogrammaAdConsent`.

Per completare l’integrazione reale:

1. crea e configura l’account Google AdSense per il banner;
2. crea in Google Ad Manager un’unità pubblicitaria di tipo rewarded;
3. inserisci gli ID e gli snippet Google in `index.html`;
4. sostituisci il link informativo con la Privacy Policy del progetto;
5. verifica il comportamento del consenso prima di pubblicare annunci personalizzati.

Gli annunci Google non sono ancora attivi finché non vengono inseriti il publisher ID AdSense e il percorso dell’unità pubblicitaria Ad Manager.

## Come pubblicare su Vercel

1. Apri Vercel.
2. Importa questa cartella come progetto.
3. Usa la cartella radice del progetto come root.
4. Vercel rileverà automaticamente un sito statico.
5. Il file principale è `index.html`.

## Nota

Il progetto è client-side e non usa database. Per il funzionamento base non richiede un server; la pubblicità Google e il caricamento dei font possono invece effettuare richieste verso servizi esterni.
