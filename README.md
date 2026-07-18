# Aspect Bilingual Website

One GitHub Pages repository containing both language versions.

## Structure

- `index.html` - language selector.
- `en/index.html` - English long-form page.
- `en/sh.html` - English short-form page.
- `he/index.html` - Hebrew long-form page.
- `he/sh.html` - Hebrew short-form page.
- `assets/proforma-example-en.pdf` - translated and revised English pro forma.
- `assets/proforma-example-he.pdf` - revised Hebrew pro forma.

`short.html` is also available in each language folder as an alias for `sh.html`.

## Language switching

Each full and short page includes a visible switch to the corresponding page in the other language, including on mobile screens.

## PDF behavior

The PDF iframe/embedded preview has been removed. Each long-form page provides a same-origin download link with the HTML `download` attribute. The English page downloads the English PDF, and the Hebrew page downloads the Hebrew PDF.

## Deployment

Publish the repository root with GitHub Pages. All website and asset paths are relative, so the site works from either a project page or a custom domain.
