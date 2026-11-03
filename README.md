# DicomDoodle website

The download page of DicomDoodle, served by GitHub Pages at <https://dicomdoodle.github.io/>.

| File | What it is |
|---|---|
| `index.html` | the whole page, styles and script included |
| `404.html` | the "page not found" page |
| `assets/` | pictures: the app's screenshots (`shots/`), the MRI slice at the top, the mascot, the link preview (`og-image.png`) |
| `favicon.ico` | the icon in the browser tab |
| `.nojekyll` | tells GitHub Pages to serve the files as they are |

## Two downloads

From DicomDoodle 2.1 the installer has no AI models: they are a second download,
the **model card** (`DicomDoodle-ModelCard-<version>.ddcard`), attached to its own
release `model-card-<version>`. The page offers both, in the download box (step 1
the program, step 2 the AI models) and in the install steps.

## A new version of DicomDoodle or of the model card

Nothing to change. The page asks GitHub for the latest release of
[pushplochan/DicomDoodle](https://github.com/pushplochan/DicomDoodle/releases)
(the installer, `*-Setup.exe`) and for the `model-card-…` release with the
highest version (the `.ddcard` file), and shows the version, size, date, SHA-256
and download link of each. The values written in `index.html` (search for
`2.1.0` and `ModelCard-1.0`) are used only when those requests fail, so update
them when convenient.

## A different address

If the site is served from another address than `https://dicomdoodle.github.io/`,
change that address in the three lines under *The site's address* in `index.html`,
and the `/` links in `404.html`.
