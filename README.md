# Yangsheng Mei — academic website

Quarto source for https://yangshengmei.com. GitHub Actions renders and publishes pushes to main.

## Structure
English is the default. Every main page has a Chinese counterpart named `*-zh.qmd`. The language control preserves the current section. English navigation: Home, Research, Teaching, Urban Memory, CV, Beyond Economics, Contact. Writing and Photography are grouped under Beyond Economics; the old URLs remain as short forwarding pages.

## Updating content
Edit the corresponding English and Chinese `.qmd` pages together. `navigation.html` localizes navigation and maps language pairs. `styles.css` controls the shared layout.

`atlas.js` contains selected public research records in English and Chinese and the interactive rendering code. Source dates, evidence status, working hypotheses and next steps should be updated together. Never put private notes into this public file, even if they would be hidden in the interface. Survey URLs must be HTTPS; embedded questionnaires may require provider permission. The offline management workspace does not automatically publish changes.

Teaching is summarized from the author's Teaching.md as a developing philosophy. Proposed modules are explicitly not presented as courses already taught. The CV page is a concise academic profile; the older local PDF contains out-of-date and private contact information and is not published.

## Publication
Commit source changes to https://github.com/yangsheng-mei/yangsheng-mei.github.io. The existing Publish Quarto website workflow builds and deploys the website. Keep CNAME as yangshengmei.com. Do not upload the private Urban-Memory-Workspace directory.
