# rfctech-brand

The RFC Tech look in one place: neutral grays, the brand blue, the 44px grid texture and the logo mark. Used by the site (`rafaelfcorrea/rfctech`) and the apps (`rafaelfcorrea/rfctech-apps`).

- `brand.css` defines raw values as `--rfc-*` CSS variables. Each project imports it once and maps its own names (`--bg`, `--mist`, ...) to these, so a color changes here and nowhere else.
- `monogram.svg` is the logo mark. Projects that need it to follow a theme render the same shapes inline.

Install pinned to a commit: `pnpm add github:rafaelfcorrea/rfctech-brand#<commit>` (or `yarn add`), then `import "rfctech-brand/brand.css"` before the project's own styles.

This repo is public. It holds only things the live site already shows; nothing private goes here.
