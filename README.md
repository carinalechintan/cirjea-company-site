# CIRJEA COMPANY - site separat

Proiect static (HTML/CSS/JS) pentru prezentarea companiei CIRJEA.

## Structura

- index.html
- style.css
- script.js
- CNAME
- .github/workflows/deploy-pages.yml

## Rulare locala

Deschide fisierul `index.html` in browser.

## Publicare separata

Acest folder este pregatit ca site independent.

1. Creeaza un repository nou pe GitHub, de exemplu `cirjea-company-site`.
2. Copiaza tot continutul acestui folder in repository-ul nou.
3. Daca folosesti GitHub Actions, lasa workflow-ul din `.github/workflows/deploy-pages.yml` activ.
4. Activeaza GitHub Pages pentru repository-ul nou.
5. Leaga domeniul `cirjeacompany.ro` din `CNAME` si din setarile Pages.

## Observatie

Repository-ul principal poate ramane pentru homepage-ul Irinei Morar, iar acest site separat poate fi publicat pe domeniul `cirjeacompany.ro`.

