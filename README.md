# Calcolo strutturale - GitHub Pages static root

Questa versione è pronta per GitHub Pages senza build.

## Pubblicazione

1. Cancella i vecchi file dal repository GitHub.
2. Carica direttamente questi file nella root del repository:
   - `index.html`
   - `assets/`
   - `README.md`
   - `_source/` opzionale
3. Vai in `Settings > Pages`.
4. Imposta:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Salva e attendi il deploy.

La cartella `_source` contiene il codice sorgente React solo per archivio/modifiche future. La pagina pubblica usa `index.html` e `assets/` presenti nella root.
