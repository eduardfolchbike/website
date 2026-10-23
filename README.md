# eduardfolch.bike

Web personal d'Eduard Folch en català, castellà i anglès, amb el joc **Carril Bici** (botó *Play game*), la secció **Explora** i la cargobike amb paquets de projectes.

## Fitxers
- `index.html`: el web sencer (HTML, CSS i JavaScript, sense dependències).
- `content.json`: textos editables, correu de contacte i projectes. Si falta o té errors, el web mostra els textos per defecte.
- `.pages.yml`: configuració de l'admin Pages CMS.
- `404.html`: fa que `eduardfolch.bike/<identificador>` porti al projecte; si no existeix, mostra una pàgina d'error.
- `CNAME`: domini eduardfolch.bike (GitHub Pages).

## Editar els textos (admin)
1. Entra a https://app.pagescms.org i inicia sessió amb GitHub.
2. Instal·la la GitHub App de Pages CMS al repositori `website` (només cal la primera vegada).
3. Obre el repositori → **Textos del web**, canvia el que vulguis i desa.
4. Cada desament fa un commit a `main` i GitHub Pages publica el canvi en 1-2 minuts.

Per afegir un projecte nou: a **Projectes**, afegeix un element, posa-li un identificador (ex. `canvis-en-cadena`) i omple com a mínim el nom en un idioma. Apareixerà com a paquet a la cargobike, a Explora i a `eduardfolch.bike/identificador`.

Si el projecte té una pàgina pròpia dins del web (camp **Apartat dins d'eduardfolch.bike**, ex. `/guia-mobilitat-escolar/`), el paquet, Explora i la ruta curta hi porten directament, sense passar per la fitxa.
