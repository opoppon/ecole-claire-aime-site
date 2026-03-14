# Description

Inspiré du template https://github.com/anthonylan/angie

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                                                  | Action                                      |
| :------------------------------------------------------- | :------------------------------------------ |
| `nvm use ; npm install                               `   | Installs dependencies                       |
| `nvm use ; npm run dev -- --port 9000 --hosts 0.0.0.0`   | Starts local dev server at `localhost:4321` |
| `nvm use ; npm run build                               ` | Build your production site to `./dist/`     |
