# Nix CN Web

## Contribution

1. **Root docs serve the zh-CN version** *[MUST]*
2. **Use sign-off via `git commit -s`** *[MUST]*
3. **Do not modify the `main` branch for any reason** *[MUST]*
4. **Do not omit the commit subject for any reason** *[MUST]*
5. **Describe all changes in the commit message** *[MUST]*
6. **Rebase before submitting patches** *[MUST]*
7. **Split commits for large or multi-part changes** *[OPTION]*
8. **Use OpenPGP/SSH for commit signing** *[OPTION]*
9. **Have fun contributing :)** *[VERY NECESSARY]*

## Toolchain

- Zed Editor
- Node 22
- Yarn v2
- Cloudflare

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `yarn install`             | Installs dependencies                            |
| `yarn dev`             | Starts local dev server at `localhost:4321`      |
| `yarn build`           | Build your production site to `./dist/`          |
| `yarn preview`         | Preview your build locally, before deploying     |
| `yarn astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `yarn astro -- --help` | Get help using the Astro CLI                     |
