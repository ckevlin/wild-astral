# Wild Astral website

Plain static site: five HTML pages and an `assets/` folder. No build step.

- `index.html` home
- `plants.html` plant glossary
- `harvests.html` list of harvests
- `harvest.html` template for one harvest (copy it for each new one)
- `shop.html` shop, links out to Etsy

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. In Vercel: Add New > Project > import the repository. Framework preset "Other", no build command, output directory left blank.
3. In the project: Settings > Domains > add your domain and follow the DNS instructions shown.

## Before going live

Search the files for `[` to find the remaining placeholders (prices, market details, harvest entries, product blurbs, bios). The "Buy on Etsy" links go to the shop front; swap in each listing URL once the listings exist.
