# Etichette — versione GitHub Pages

Sito statico: non richiede Python, server o installazione. I PDF vengono elaborati nel browser e non vengono caricati su un backend.

## Pubblicazione su GitHub Pages
1. Crea un repository GitHub chiamato `etichette`.
2. Carica `index.html` nella cartella principale del repository.
3. Apri **Settings → Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**.
5. Seleziona `main` e `/ (root)`, poi premi **Save**.
6. Attendi la pubblicazione. Il sito sarà disponibile a `https://TUO-USERNAME.github.io/etichette/`.

## Uso
Apri il sito da telefono o computer e premi **Seleziona i PDF**. Dopo l'elaborazione verrà scaricato `etichette_ottimizzate_A4.pdf`.

## Note importanti
- Le pagine PDF sorgenti vengono ritagliate e inserite nel PDF finale senza rasterizzarle.
- Le etichette non vengono intenzionalmente ridimensionate; il programma può ruotarle di 90°.
- Il riconoscimento del rettangolo è automatico e basato su una euristica visiva. Alcuni modelli di etichetta possono non essere riconosciuti correttamente: controllare il risultato prima di stampare.
- La disposizione cerca di ridurre i fogli, ma non garantisce una soluzione matematica globalmente ottima.
- Le librerie PDF.js e pdf-lib sono caricate da CDN; serve una connessione Internet.
- Per stampare usare "dimensioni effettive" / 100%, senza "adatta alla pagina".
