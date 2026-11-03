# DicomDoodle website

The download page of DicomDoodle, served by GitHub Pages at <https://dicomdoodle.github.io/>.

| File | What it is |
|---|---|
| `index.html` | the whole page, styles and script included |
| `404.html` | the "page not found" page |
| `assets/` | pictures: the app's screenshots (`shots/`), the MRI slice at the top, the mascot, the link preview (`og-image.png`) |
| `favicon.ico` | the icon in the browser tab |
| `.nojekyll` | tells GitHub Pages to serve the files as they are |

## A new version of DicomDoodle

Nothing to change. The page asks GitHub for the latest release of
[pushplochan/DicomDoodle](https://github.com/pushplochan/DicomDoodle/releases) and shows
its version, size, date, SHA-256 and download link. The values written in
`index.html` (search for `2.0.0`) are used only when that request fails, so
update them when convenient.

## A different address

If the site is served from another address than `https://dicomdoodle.github.io/`,
change that address in the three lines under *The site's address* in `index.html`,
and the `/` links in `404.html`.
