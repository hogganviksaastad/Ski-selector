[README.md](https://github.com/user-attachments/files/28198879/README.md)
# Ski Selector (GitHub Pages)

Dette repoet er en hostet webversjon av **Håkons vanskelige skivalg** bygget fra arbeidsboken `Håkons vansklige skivalg_V2.xlsx`.

## Innhold
- `index.html` – app-shell
- `style.css` – mobiloptimalisert UI
- `script.js` – full scoringsmodell + rendering
- `.nojekyll` – sørger for at GitHub Pages serverer filene som vanlig statisk side

## Publisering på GitHub Pages
1. Last opp alle filene i dette repoet til en public GitHub-repo.
2. Gå til **Settings → Pages**.
3. Velg **Deploy from branch**.
4. Velg branch **main** og mappe **/root**.
5. Åpne URL-en GitHub oppgir, typisk:
   `https://<brukernavn>.github.io/<repo-navn>/`

## Verifisert standardscenario
- Løype: `Svart`
- Trasebredde: `Medium`
- Snow conditions: `harde`
- Riding style: `Aktivt`
- Skill level: `Advanced`
- Turn shape: `Kort–medium`

For dette scenarioet gir modellen:
- Vinner: **Stöckli Laser WRT PRO (172cm)**
- Score: **9.35**

## Merk
- Denne siden bruker JavaScript og er ment å kjøres **hostet i nettleser** (f.eks. GitHub Pages), ikke som lokal iPhone-filpreview.
