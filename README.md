# Degrees of Lewdity: X-Change Edition — compiled build (storage-fallback fork)

Play: https://redcommand025.github.io/dol-xchange-localstorage-comp/

This repo is a ready-to-serve compiled build (GitHub Pages) of
[redcommand025/dol-xchange-localstorage](https://github.com/redcommand025/dol-xchange-localstorage)
at commit `5972f25ebcd74d726a6e34d3c9b3249e2a38e5d4`. That repo is
[Akoz/dol-xchange](https://gitgud.io/Akoz/dol-xchange) (upstream commit `ddb1cf03`, version
`0.5.13.8 DoLP v0.778 DoLX 0.22.5`) plus a fallback that lets the game start when the browser blocks
localStorage/IndexedDB.

Contents: `index.html` (built with `./compile.sh`, storage fallback prepended), plus `img/`, `img2/`,
`audio/` and `style.css` from the source commit. Audio is stored in upstream Git LFS; the real MP3s are
committed here as plain files (hash-checked against the LFS pointers) because GitHub Pages does not serve LFS content. Image packs `imagepacks/au` (Aoki Utage Fem), `imagepacks/aumasc` (Aoki Utage Masc) and
`imagepacks/mysterious` (Mysterious combat sprites) are included and selectable in Options > Images.

Credits: Degrees of Lewdity by Vrelnir and contributors; DoLPlus by Frostberg and contributors;
X-Change Edition by Akoz and contributors. Licensed under CC BY-NC-SA 4.0 (see `LICENSE`), same as upstream.
