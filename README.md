# Description

Inspiré du template https://github.com/anthonylan/angie

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                                                    | Action                                      |
| :---------------------------------------------------------- | :------------------------------------------ |
| `mise install ; npm install                               ` | Installs dependencies                       |
| `mise install ; npm run dev -- --port 9000 --hosts 0.0.0.0`  | Starts local dev server at `localhost:4321` |
| `mise install ; npm run build                              ` | Build your production site to `./dist/`     |

La version de Node.js utilisée est définie dans `.mise.toml`. `mise` bascule automatiquement dessus en entrant dans le dossier du projet (voir [mise-en-place](https://mise.jdx.dev)).


## Déploiement
Executer le build

mise install && npm run build && rsync -avz --delete dist/ debian@152.228.140.231:/var/www/ecole-claire-aime/
