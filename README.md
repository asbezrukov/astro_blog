# Astro Demo Tutorial

## 💡 Project summary

This is my first Astro project made by [the official tutorial](https://docs.astro.build/en/tutorial/0-introduction/). It was made for a few hours. 

**What I learned from this:**

- Astro page, layout and component structure is easy and scalable for fast component-based development
- The difference between server-side and client-side building and js execution are clear and manageble
- I could use native templates or html generation from markdown for many cases
- Static and dynamic routing could be useful for logic separation and website' search engine optimisation.
- If I have to use some React/Vue plugin, it'll be easy to encapsulate them to an island.

Blog published with Netlify: [open published website](https://astro-blog-examlple.netlify.app/) - I didn't bother about style, my goal was to get to know with framework.

**What I'll do with my new knowledge:**

- I'll use Astro for my personal website, because it's fast and easy to maintaine.
- If I have to build a simple web-site without UGC, auth and complex db queries, I'll consider to use Astro for frontend.
- I'd like to try Astro with some backend service with REST endpoints or GraphQL. It should work smooth.


## 🚀 Project Structure

```text
/
├── public/
├── src/
│   ├── blog/
│   ├── componentss/
│   ├── layouts/
│   └── pages/
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
