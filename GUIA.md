# Hedge Honcho: posar-lo online (GitHub Pages) i fer l'APK

## 1. Pujar el joc a GitHub Pages (gratis, ~5 min)
1. Crea un compte a https://github.com (si no en tens).
2. Toca **+** (a dalt a la dreta) → **New repository**. Nom: `hedge-honcho`. Marca **Public**. Toca **Create repository**.
3. Toca **uploading an existing file** i arrossega-hi **tots els fitxers de dins la carpeta** (no el zip ni la carpeta): `index.html`, `manifest.json`, `sw.js` i les 3 icones `.png`. Toca **Commit changes**.
4. Ves a **Settings → Pages**. A *Branch* tria `main` i la carpeta `/ (root)`. Toca **Save**.
5. Espera 1-2 minuts. La teva URL serà: `https://EL_TEU_USUARI.github.io/hedge-honcho/`

Passa aquesta URL als amics. Ja funciona amb multijugador.

## 2. Instal·lar-lo com a app (sense APK)
- **Android (Chrome):** ⋮ → *Instal·la l'aplicació* / *Afegeix a la pantalla d'inici*.
- **iPhone (Safari):** botó Compartir → *Afegeix a la pantalla d'inici*.

## 3. APK per a Android (opcional)
1. Ves a https://www.pwabuilder.com i enganxa la teva URL de GitHub Pages. Toca **Start**.
2. Toca **Package for stores** → **Android** → **Generate package** (opció per defecte, gratis).
3. Es baixa un zip amb l'APK. Envia l'APK als amics.
4. Als mòbils han d'activar *Instal·lar apps de fonts desconegudes* (només el primer cop).

## Multijugador
Tothom escriu el mateix **codi de sala**, toca **Multijugador** i després **Llest!**. Comença quan tots estan llestos (mínim 2). Necessita internet. Sense connexió, el mode d'un jugador funciona igualment.

## Si el multijugador no connecta
- Comprova que tots tenen internet i escriuen exactament el mateix codi.
- Algunes xarxes (wifi d'escola, feina) bloquegen WebRTC. Prova amb dades mòbils.
- Si has canviat el joc i no veus els canvis, tanca l'app i torna-la a obrir (la memòria cau s'actualitza al segon cop). Si fas canvis grans, canvia `hedge-honcho-v1` a `sw.js` per `v2`.
