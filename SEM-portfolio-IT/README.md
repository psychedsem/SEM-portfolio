# SEM — Portfolio personale

Portfolio personale sviluppato per il progetto finale HTML e CSS.

## Pagine

- `index.html` — Home, focus, competenze e aree dei progetti
- `data-analysis.html` — Data Analysis
- `data-manipulation-visualization.html` — Data Manipulation & Visualization
- `machine-learning.html` — Machine Learning
- `full-stack-development.html` — Full-Stack Development
- `ai-agents.html` — AI Agents, attualmente Work in Progress
- `3d-graphics.html` — 3D Graphics, attualmente Work in Progress
- `cv.html` — CV in HTML
- `contact.html` — pagina Contatti con form e campi `required`

## Tecnologie e requisiti implementati

- HTML5 semantico
- CSS responsive
- Flexbox
- CSS Grid
- Bootstrap 5.3.8 tramite CDN
- Sass/SCSS organizzato in partial
- menu sticky e responsive senza JavaScript
- favicon SVG
- metadati Open Graph
- form accessibile
- stile di stampa per il CV
- supporto a `prefers-reduced-motion`
- card progetto responsive con cover 16:9 e link esterni sicuri (`rel="noopener noreferrer"`)

## Progetti inseriti

### Data Analysis
- TerraTextiles
- The Green Whisper
- Shifting Gears

### Data Manipulation & Visualization
- LookBook
- GreenGap - Habits Unlocked
- Appetite for Disruption
- The Content Blueprint

### Machine Learning
- Who Survived the Titanic?
- Beyond the Diagnosis

### Full-Stack Development
- DnA — Science Magazine

Le sezioni AI Agents e 3D Graphics sono mantenute nel portfolio come aree Work in Progress.

## Come aprirlo

1. Estrai la cartella.
2. Aprila con Visual Studio Code.
3. Apri `index.html`.
4. Con Live Server: tasto destro su `index.html` → `Open with Live Server`.

## Sass

Il browser legge `css/main.css`, mentre i sorgenti Sass sono nella cartella `scss/`.

Per ricompilare gli SCSS:

```bash
npm install
npm run build
```

Per lavorare con compilazione automatica durante le modifiche:

```bash
npm run sass
```

## Passaggi finali

- pubblicare il portfolio su GitHub Pages;
- sostituire `og:image` con un URL assoluto dopo la pubblicazione;
- collegare opzionalmente il form a un servizio di invio email;
- effettuare l’ultimo controllo cross-browser e mobile;
- aggiungere in futuro i progetti AI Agents e 3D Graphics.
