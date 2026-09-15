# Istruzioni per il monogramma

## Obiettivo

Il generatore deve produrre monogrammi geometrici circolari o quadrati, coerenti con i due riferimenti:

- `alfabetocircolare.png`
- `alfabetoquadrato.png`

Le immagini sono la fonte visiva principale. Evitare interpretazioni tipografiche libere.

## Regole geometriche

- Mantenere proporzioni, spessori, punti di contatto e allineamenti del riferimento.
- Trattare alfabeto circolare e quadrato come sistemi distinti; non deformare un sistema per ottenere l’altro.
- Centrare ogni lettera rispetto al frame.
- Nel cerchio, fare aderire curve e tratti al bordo senza sforamenti o vuoti evidenti.
- Evitare sovrapposizioni, schiacciamenti e deformazioni.

## Modifiche alle lettere

Ogni intervento deve essere locale:

1. confrontare la lettera con il riferimento corretto;
2. individuare il solo tratto da correggere;
3. applicare la modifica senza alterare le altre lettere;
4. verificare centratura, aderenza e pulizia del risultato.

Indicazioni ricorrenti:

- `G` circolare: adattare il modello al bordo del cerchio;
- `B`, `P`, `R`: mantenere lo stelo verticale allineato;
- `S`: conservare una curva chiara e non distorta.

## Funzioni del generatore

- frame circolare o quadrato, visibile o nascosto;
- ridimensionamento locale della lettera selezionata;
- controllo dello spessore del tratto;
- export SVG e PNG.

Ogni risultato deve restare leggibile, centrato e dentro il frame scelto.
