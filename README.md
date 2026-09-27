# Camden da Silva — portfolio site (Tesla Terafab version)

Same site as camden1245.github.io, with one new project added at the top: the High-NA EUV field-stitching simulation, marked as in progress.

Every file sits at the top level — no subfolders — so you can select them all and upload them in one go.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site — text and styling in one file |
| `*.png`, `*.jpg` | Figures and photos used on the page |
| `portfolio.pdf` | The PDF portfolio, linked from the header and footer |

## Two stitching figures to add yourself

The page looks for these two files, using the same names your simulation saved them under:

- `fig07_failure_maps.png`
- `fig09_failure_probability.png`

Drop them in next to `index.html` when you upload. Until they are there, those two figures stay hidden, so the page never shows a broken image.

## Putting it online (separate repo)

1. On GitHub, create a new public repository, for example `terafab`.
2. Click **Add file → Upload files**, select every file in this folder at once, and commit.
3. Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Wait a minute or two, then open `https://camden1245.github.io/terafab/`.

Your main site at camden1245.github.io is not touched by any of this.
