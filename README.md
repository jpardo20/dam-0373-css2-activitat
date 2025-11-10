
# DAM 0373 — Activitat ***CSS clàssic (CSS2)***

## Enunciat (resum)
1) **Qüestionari** (`q-css2.md`): teoria de selecció, cascada, herència, box model, posicionament.
2) **Mini‑maquetació clàssica:** estilitza `index.html` només amb CSS **clàssic** (no Flex, no Grid, no `var()`, no `:is/:has/:where`, etc.).
3) **Autoavaluació** (`AUTO.md`).

### Requisits clau (resum)
- Dues columnes amb **floats** o `position`, *clearfix* o conteniment del flux.
- **LVHA**: estats `a:link`, `a:visited`, `a:hover`, `a:active` diferenciats.
- Taula `.dades` bàsica amb `border-collapse` i capçalera diferenciada.
- Regles d’impressió `@media print` mínimes.

> L’HTML es pot tocar **només** per afegir `id`/`class` i contingut (no canvies l’estructura).

## Com provar localment
Necessites **Node 18+**. Al directori del projecte:

```bash
npm ci
npm test             # executa validació HTML, lint CSS i comprovacions de normes
```

- **HTML**: es valida amb [`html-validate`](https://html-validate.org/).
- **CSS**: es comprova amb `stylelint` i regles bàsiques.
- **Regles de l’activitat**: scripts que vetllen per “no Flex/Grid/vars…” i que hi hagi LVHA, `@media print`, taula, etc.

## Lliurament
- Puja els fitxers al repo i verifica que l’**Autograder** d’aquest assignment marca verd.
- Arxius requerits: `index.html`, `styles.css`, `q-css2.md`, `AUTO.md`.

