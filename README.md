# mparto.de

Professional site of Michael Arman Partovifar. A one-page [Hugo](https://gohugo.io/) site in six languages (ES, EN, DE, FR, RU, AR), with light and dark themes. No theme, no frameworks, no dependencies beyond Hugo. Deployed on Netlify.

## Run locally

```
hugo server
```

Requires Hugo v0.158 or newer.

## Structure

```
layouts/index.html        the page (one template for every language)
layouts/partials/         language menu, background network, hero graphic
layouts/robots.txt        robots template
i18n/*.yaml               all text, one file per language
assets/css/site.css       styles
assets/img/michael.png    portrait and favicon source
static/site.webmanifest   web app manifest
hugo.toml                 languages and links
netlify.toml              build, headers, redirects
```

## License

The code (templates, styles, config) is MIT licensed: reuse it freely. The personal content (photo, all text in `i18n/`, name and contact details) is all rights reserved and may not be reused. See [LICENSE](LICENSE).
