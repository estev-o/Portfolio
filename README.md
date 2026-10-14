# Portfolio

Personal portfolio with a retro terminal look, built with plain HTML and CSS (no JavaScript, no build step).
Live at <https://estev-o.github.io/Portfolio/>.

## Structure

```
index.html            English home (default language)
pages/                English pages: about, experience, projects, knowledge
es/index.html         Spanish home
es/pages/             Spanish pages (same file names as pages/)
assets/css/styles.css Shared styles, including the EN/ES language switch
assets/images/        Images used in the pages
```

Every page exists in both languages with the same file name, so the language switch
(`lang> [EN] ES`, top-right corner) always links to the same page in the other language.
When updating content, change both `pages/` and `es/pages/`.

## TODO

- Expand the Master's (IMCV) course entries in the Knowledge page as the semester progresses.
- Add the XoveTIC 2026 DOI once it is assigned.
