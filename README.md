
# DAM 0373 — Activitat “CSS clàssic (CSS2)” — *Template Classroom*

> **Durada a classe:** 2 h (lectura prèvia del curs històric CSS2).  
> **Modalitat:** individual (o parelles, nota individual).

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

## Per al docent
- Aquest repo és **template** per GitHub Classroom.  
- Porta **autograding** amb punts (100) i *workflow* per avaluació.

### Com publicar com a Template i crear Assignment
1. Crea un repo amb aquest contingut i, a **Settings → General**, activa **Template repository**.  
2. Si cal, fes-lo **public** o propietat de l’**organització** del Classroom (recomanat).  
3. A **GitHub Classroom**, crea **Assignment** i tria aquest **template**.  
4. (Opcional) No afegeixis tests via GUI si **ja** portes `.github/classroom/autograding.json` + `classroom.yml` en el template.

> Referència: “Create an assignment from a template repository” i “Creating a template repository” a la documentació oficial de GitHub.

---

© 2025 — DAM 0373 (ús docent).
