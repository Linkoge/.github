# Linko organization profile

The public organization landing page lives in [`profile/README.md`](profile/README.md).

## Brand assets

The theme-aware hero artwork in `profile/assets/` reuses the original vector paths
from [Linko’s public website logo](https://linko.ge/assets/logo-white.svg).
The wordmark is preserved; the red accent matches the October 5 logo editor
(15 vector units left and 6 up). The light variant uses `#11141a`,
Linko’s website background color, for the wordmark. The surrounding network
linework is decorative and makes no claim about a specific deployed topology.

The capabilities artwork is laid out as three columns on desktop and three rows on
mobile. Separate hero crops keep the logo prominent on smaller screens. GitHub’s
light/dark link fragments select the theme; picture sources select the layout.
All image content has descriptive alternative text.

The profile uses GitHub-compatible HTML and Markdown without custom CSS or scripts.
Only public website branding and verified public project information are included.
Python, JavaScript and Playwright are used by the featured Linko Dev Panel project.

## Design experiments

The original hero SVGs are preserved in
[`profile/assets/backup/2026-10-05-original/`](profile/assets/backup/2026-10-05-original/).

The temporary, standalone design page is `assets/linko logo/design-lab.html`
in the `cryptiama/Linko` website repository. It embeds original and updated
artwork, lets you change background color and crop, and exports vector SVG
or PNG up to 9600 pixels wide. It works offline without fonts or libraries.
