# djcaddy-site

La pagina di download di [DjCaddy](https://mspadaccino.github.io/djcaddy-site/)
e, nelle Release, il DMG. Il codice dell'app sta in un altro repo, privato.

La pagina è `index.html`, statica: l'Action in `.github/workflows/pages.yml`
la pubblica su GitHub Pages a ogni push su `main`. Il DMG lo carica
`packaging/release_github.sh` dal repo dell'app, in una Release `v<versione>`
col nome fisso `DjCaddy.dmg`, che è il link «latest» a cui la pagina punta.
