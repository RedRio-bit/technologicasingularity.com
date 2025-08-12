# RedRioLab — GitHub Pages Starter

Questo pacchetto è pronto per essere caricato su **GitHub Pages**.

## Come usarlo
1. Crea un nuovo repository pubblico su GitHub (es. `sito`).
2. Carica tutti i file di questa cartella.
3. Nel repo: **Settings → Pages** → Source: `main` / `/root` → salva.
4. (Opzionale) In **Settings → Pages → Custom domain** inserisci il tuo dominio.

## DNS su GoDaddy (dominio personalizzato)
Imposta per il dominio i seguenti record:
- **A** → `185.199.108.153`
- **A** → `185.199.109.153`
- **A** → `185.199.110.153`
- **A** → `185.199.111.153`
- **CNAME** (host `www`) → `username.github.io` (sostituisci con il tuo username).

> Suggerimento: puoi usare due domini diversi puntando agli stessi record.
La propagazione può richiedere fino a 24 ore.

## Personalizzazione
- Modifica `index.html` e `assets/style.css`.
- Puoi aggiungere altre pagine (es. `about.html`) e linkarle dal menu.
- Per forzare HTTPS e dominio custom puoi anche aggiungere un file `CNAME` con il dominio (uno solo). In alternativa imposta il dominio dalle **Settings** del repo.

Buon lavoro!
