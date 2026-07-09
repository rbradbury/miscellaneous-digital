# miscellaneous.digital

One-page site for Miscellaneous Digital, a holding company for a drawer of small, useful apps.

- Static site: everything lives in `index.html` (no build step, no dependencies).
- Hosted on Vercel; pushes to `main` deploy automatically.

## Local preview

```sh
npx serve .
```

## Editing the app catalog

App entries are the `.entry` blocks in `index.html`. Copy one, bump the number, update the name, description, link, and status stamp.
