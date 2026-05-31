# The Collected Treasures of Dudjom Lingpa &middot; Translation Project

A scholarly English & Rioplatense Spanish translation of the revealed-treasure corpus of **Bdud-'joms Gling-pa** (Dudjom Lingpa, 1835–1904), undertaken from the 2004 Lama Kuenzang Wangdue edition (TBRC W28732).

Translated by **Lama Federico Andino** (Lama Fede, [vajrakula.com](https://www.vajrakula.com)) and **Lama Dorje Sherab** (Johnathan Justinn).

**Repository:** [github.com/Dingirfecho/dudjom-lingpa](https://github.com/Dingirfecho/dudjom-lingpa)

## About this site

This repository hosts the project's public-facing site, presenting:

- The current state of the translation effort (4 of 21 volumes complete)
- A short biography of Dudjom Lingpa
- Volume-by-volume synopses of the four completed volumes
- The lineage-context of the translation, as set out in the *Garland of Lives Prayer*

The site is bilingual (English / Rioplatense Spanish), with a language toggle in the top-right corner.

## Local preview

The site is plain static HTML. To preview it locally:

```bash
# from the repo root
python3 -m http.server 8000
# then open http://localhost:8000
```

No build step is required.

## Deployment to GitHub Pages

The site is served directly from this repository's root. The `.nojekyll` file disables Jekyll processing so the HTML is served as-is.

To enable Pages:

1. Push the contents of this repo to **github.com/Dingirfecho/dudjom-lingpa**.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Select **main** branch, **/ (root)** folder.
5. Save. The site will be available at **https://dingirfecho.github.io/dudjom-lingpa/**.

For a custom domain (e.g. `dudjom.vajrakula.com`), add a `CNAME` file at the root containing the bare domain and configure DNS per [GitHub's documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Source edition

> *Sprul pa'i gter chen Bdud 'joms gling pa'i zab gter gsang ba'i chos sde*
> 2004 Lama Kuenzang Wangdue · Motithang Palace, Thimphu, Bhutan
> KMT Press, Phuentsholing
> TBRC W28732

## Dedication

*May this work be for the benefit of wandering beings.*

*Que esta obra sea para el beneficio de los seres errantes.*

