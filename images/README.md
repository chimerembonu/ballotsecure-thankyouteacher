# Logo files

Drop the two official logo files into this folder using **exactly** these names:

| File name        | Logo                                          | Where it appears        |
|------------------|-----------------------------------------------|-------------------------|
| `gnat-logo.png`  | GNAT Logo transparent                         | Navigation bar          |
| `tyt-logo.png`   | LOGO TYT transparent                          | Hero section (centred)  |

PNG with a transparent background is expected (SVG also works — if you use SVG,
update the two `src` attributes in `index.html` to `.svg`).

Until these files exist, `index.html` falls back to a temporary text logo, so the
site never shows a broken image.

Note: both logos are dark artwork on a transparent background, so they are placed
on a white chip (nav) and a white panel (hero) to stay legible against the navy
background. If reversed/white versions of the logos are available, those can be
used instead and the white backing removed.
