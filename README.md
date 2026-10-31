# Debendra Kumar Swain — academic website

Built with the official **Hugo Blox Academic CV** template (MIT license).

Website: https://debenswain.github.io/debendra/

## Edit content

- Profile: `data/authors/me.yaml`
- Homepage: `content/_index.md`
- Research, teaching, talks, CV: corresponding folders under `content/`
- Publications: `content/publications/<article>/index.md` and `cite.bib`
- Profile photo: `assets/media/authors/me.jpg`
- Downloadable academic CV: `static/uploads/Debendra_Kumar_Swain_CV.pdf`
- Colours and appearance: `config/_default/params.yaml`
- Navigation: `config/_default/menus.yaml`

## Local development

Install Hugo Extended 0.161.1, Go, and Node.js 22 or later. Then:

```sh
npm install
hugo server --disableFastRender
```

Build: `npm run build`.

## Deployment

The workflow builds and publishes on every push to `main`.
In repository Settings → Pages, select **GitHub Actions** as the source.

The public CV is a website edition prepared from the supplied CV, with personal/family information and private phone/address details omitted. Article links use publisher DOIs; the CMAM article is cited by its 2025 issue year, with its 2024 online date noted.

## Credits

Template: https://github.com/HugoBlox/hugo-theme-academic-cv
Theme license: `LICENSE.md`. Personal text and photographs remain the author's.
