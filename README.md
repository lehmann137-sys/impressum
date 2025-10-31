# Impressum-Website

**Stand:** 2025-10-31

Dies ist eine einfache, statische Website mit deinem Impressum (`index.html`). Du kannst sie überall hosten.

## Schnellstart (ohne Code)

### Option A: Netlify (super einfach)
1. Gehe auf https://app.netlify.com/drop
2. Ziehe den kompletten ZIP-Ordner hier rein.
3. Netlify gibt dir sofort eine URL (z. B. `https://dein-name.netlify.app`).
4. (Optional) Eigene Domain verbinden: **Site → Domain management → Add custom domain** und DNS-Eintrag setzen.

### Option B: GitHub Pages
1. Erstelle ein neues Repo auf GitHub, z. B. `impressum`.
2. Lade `index.html` (und die restlichen Dateien) hoch.
3. Einstellungen → **Pages** → Source: **Deploy from a branch**, Branch: `main` (root).
4. Öffentliche URL erscheint (z. B. `https://deinname.github.io/impressum`).

### Option C: Vercel
1. Gehe zu https://vercel.com/new
2. Importiere ein GitHub-Repo **oder** lade das ZIP als neues Projekt hoch.
3. Nach dem Deploy erhältst du eine URL (z. B. `https://impressum.vercel.app`).

### Option D: Eigenes Webhosting
1. Verbinde dich per FTP/Dateimanager mit deinem Hoster.
2. Lade `index.html` in das Webverzeichnis (oft `public_html` oder `www`).
3. Rufe die Domain auf.

## Eigene Domain (optional)
- Domain bei einem Registrar (z. B. Cloudflare, IONOS, Strato) kaufen.
- Im Dashboard deines Hosters **Domain verbinden** auswählen und den DNS-Hinweisen folgen.
- Warte einige Minuten, bis DNS aktiv ist.

## Dateiübersicht
- `index.html` – deine Impressumsseite
- `netlify.toml` – nur relevant für Netlify (Single-Page-Routing)

Viel Erfolg!
