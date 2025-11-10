
# DAM 0373 — Activitat "CSS clàssic (CSS2)"

> **Modalitat:** individual

## Enunciat

Basant-vos en el [Curs de CSS en català](https://jpardo20.github.io/curscss/index.php.html) cal que:

1) Respongueu el **qüestionari** (**`q-css2.md`**): teoria de selecció, cascada, herència, box model, posicionament.

> 
> Respon editant el fitxer [**`q-css2.md`**](./q-css2.md) del teu repositori.
>

2) Feu la vostra pàgina web estilitzant [**`index.html`**](./index.html) i només fent servir CSS **clàssic** ([**`styles.css`**](./styles.css)), sense fer servir ni **`Flex`**, ni **`Grid`**, ni **`var()`**, ni **`:is/:has/:where`**, etc.

> 
> Respon editant el fitxer [**`index.html`**](./index.html) del teu repositori. Cal que comenteu tot allò que feu, ja sigui dins del fitxer **`index.html`** com del fitxer **`styles.css`**.
>


### Requisits clau

- Dues columnes amb **floats** o `position`, *clearfix* o conteniment del flux.


> El contingut queda en dues columnes: **`main`** (columna principal) i **`aside`** (lateral).
> 
> Les columnes no es trepitgen i el contenidor **`content`** envolta els seus fills (no queda “col·lapsat”).
> 
> Ús de float (esquerra/dreta) o de position (absolute/relative/fixed) per aconseguir el **`layout`**.

- **LVHA**: estats diferenciats.

> Hi ha quatre regles visibles i diferenciades:
> 
> **`a:link`**, **`a:visited`**, **`a:hover`**, **`a:active`**.
> 
> Els estats es veuen diferents (color, subratllat, etc.).

- Taula `.dades` bàsica amb `border-collapse` i capçalera diferenciada.

> La taula té files amb vores i padding a les cel·les.
> 
> La fila de capçalera es distingix visualment (fons, negreta, etc.).
>

- Regles d’impressió `@media print` mínimes.

>
> Existeix un bloc **`@media print { ... }`**.
> 
> En imprimir, s’oculta la navegació i el lateral com a mínim (**`nav`**, **`aside`**).
> 
> L’ample del **`page`** s’adapta (sense la caixa fixa).
> 

**IMPORTANT**: L’HTML es pot tocar **només** per afegir `id`/`class` i contingut (no canviïs l’estructura).

## Lliurament

- Puja els fitxers: **`index.html`**, **`styles.css`**, i **`q-css2.md`** al teu repo.

