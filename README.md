# Interactive Web Projects

A collection of experimental, interactive, and visually-driven single-page web projects.

This repository contains standalone web experiences built to explore creative UI, animation, storytelling, interaction design, motion, and modern frontend techniques.

Each project lives in its own directory and can be developed, tested, and deployed independently.

---

## Repository Structure

```text
interactive-web-projects/
│
├── pointers/
│   └── Interactive pointer and hero experiments
│
├── storytelling/
│   └── Scroll-based storytelling experiences
│
├── experiments/
│   └── Experimental interactions, animations, and UI concepts
│
└── assets/
    └── Shared assets used across multiple projects
```

### `pointers/`

Interactive pointer, cursor, hero, and mouse-reactive experiences.

Examples:

* Animated cursor interactions
* Mouse-tracking characters
* Interactive hero sections
* Sprite-based character animations
* Pointer-driven visual effects

### `storytelling/`

Scroll-driven storytelling projects where animation, visual transitions, and narrative are combined into a single-page experience.

Examples:

* Scroll storytelling
* Interactive narratives
* Scene-based animations
* Product or concept stories
* Cinematic web experiences

### `experiments/`

Small experiments and prototypes that do not yet belong to a specific project category.

Examples:

* Scroll effects
* Cursor effects
* Animation experiments
* WebGL experiments
* UI interaction prototypes

### `assets/`

Shared resources that are intentionally reused between projects.

Project-specific assets should normally remain inside the corresponding project folder.

---

## Project Philosophy

These projects are primarily experiments and creative frontend experiences.

The main goals are:

* Creative interaction
* Smooth animation
* Strong visual storytelling
* Interesting user experiences
* Modern frontend techniques
* Performance-conscious implementation
* Reusable ideas and components

Projects may use different technologies depending on their requirements.

---

## Project Independence

Each project should remain as self-contained as reasonably possible.

A typical project may look like:

```text
project-name/
├── README.md
├── package.json
├── src/
├── public/
└── ...
```

Projects that do not require a build system may simply contain:

```text
project-name/
├── index.html
├── style.css
├── script.js
└── assets/
```

---

## Technologies

Depending on the project, this repository may contain projects using:

* HTML
* CSS
* JavaScript
* TypeScript
* React
* Next.js
* Vite
* Framer Motion
* GSAP
* Canvas
* WebGL
* SVG
* FFmpeg
* Sprite-sheet animation
* Other modern web technologies

Each project should document its specific stack in its own `README.md`.

---

## Running a Project

Because projects may use different technologies, always check the project's own README first.

For a typical Node.js project:

```bash
cd project-name
pnpm install
pnpm dev
```

or:

```bash
npm install
npm run dev
```

For a simple static project, open `index.html` in a browser or use a local development server.

---

## Adding a New Project

Create the project inside the appropriate category.

For example:

```text
storytelling/
└── new-story/
```

or:

```text
pointers/
└── new-interactive-pointer/
```

Every substantial project should have its own README containing:

* Project description
* Features
* Technologies
* How to run it
* Important implementation details
* Credits / external assets when applicable

---

## Git Rules

Do not commit generated or sensitive files such as:

```text
node_modules/
dist/
build/
.next/
.env
.env.*
*.log
```

Use `.gitignore` to keep these files out of the repository.

---

## Status

This repository is an evolving collection of creative web experiments and interactive experiences.

New projects will be added over time.
