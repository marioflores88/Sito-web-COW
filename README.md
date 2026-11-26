# Sito COW Entertainment

Sito istituzionale della holding COW Entertainment (Come On Web S.r.l.) e delle sue società: ETES Sport, ETES Theatre, Arena Flegrea, Make It Happen e Noisy Naples Fest.

Online su: https://marioflores88.github.io/Sito-web-COW/

- `index.html`: pagina unica con una vista per ogni sezione (`#gruppo`, `#etes-sport`, `#etes-theatre`, `#arena-flegrea`, `#make-it-happen`, `#noisy-naples-fest`, `#contatti`).
- `img/`: loghi delle società.
- `.github/workflows/pages.yml`: pubblica il sito su GitHub Pages a ogni modifica su `main` (oppure a mano da **Actions → Sito su GitHub Pages → Run workflow**).

Per vederlo in locale: `python3 -m http.server`, poi aprire http://localhost:8000.

## Dominio personalizzato

**Settings → Pages → Custom domain**: inserire il dominio (es. `www.cowentertainment.it`), creare presso il provider un record `CNAME` verso `marioflores88.github.io` e attivare **Enforce HTTPS**.
