# Degrees of Lewdity: X-Change Edition — compiled build (storage-fallback fork)

Play: https://redcommand025.github.io/dol-xchange-localstorage-comp/

This repo is a ready-to-serve compiled build (GitHub Pages) of
[redcommand025/dol-xchange-localstorage](https://github.com/redcommand025/dol-xchange-localstorage)
at commit `c5e7545fb504c5d20910b6b4970a5a3d0d29d666`. That repo is
[Akoz/dol-xchange](https://gitgud.io/Akoz/dol-xchange) (upstream commit `ddb1cf03`, version
`0.5.13.8 DoLP v0.778 DoLX 0.22.5`) plus a fallback that lets the game start when the browser blocks
localStorage/IndexedDB.

Contents: `index.html` (built with `./compile.sh`, storage fallback prepended), plus `img/`, `img2/`,
`audio/` and `style.css` from the source commit. Audio is stored in upstream Git LFS; the real MP3s are
committed here as plain files (hash-checked against the LFS pointers) because GitHub Pages does not serve LFS content. Optional image packs (`imagepacks/`) are not included.

Credits: Degrees of Lewdity by Vrelnir and contributors; DoLPlus by Frostberg and contributors;
X-Change Edition by Akoz and contributors. Licensed under CC BY-NC-SA 4.0 (see `LICENSE`), same as upstream.
