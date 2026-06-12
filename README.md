# Calcolo strutturale

Applicazione React/Vite per calcolo strutturale e predimensionamento.

## Avvio locale

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Pubblicazione su GitHub Pages

Questo progetto include già `.github/workflows/deploy.yml`.

Dopo aver caricato il repository su GitHub:

1. Vai su **Settings > Pages**.
2. In **Build and deployment**, scegli **Source: GitHub Actions**.
3. Fai un nuovo commit/push oppure apri **Actions** e lancia il workflow manualmente.
4. La pagina pubblicata userà la cartella `docs` generata da Vite. In alternativa puoi scegliere **Deploy from a branch** e impostare **main / docs**.

La configurazione `base: './'` in `vite.config.js` evita la pagina bianca tipica dei repository GitHub Pages pubblicati in sottocartella.
