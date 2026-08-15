# Mohammad and Hadeel — Wedding site

Live: https://mo7ammadzak.github.io/zak-hadeel-wedding/

## What to upload to GitHub (repo root)
- index.html  — tiny loader, never changes again. Upload it ONCE.
- site.html   — the actual website (everything embedded). Replace this file for any future change.

Both must sit at the ROOT of the repository, not inside a folder.

## First deploy
1. Repo > Add file > Upload files
2. Drag index.html AND site.html
3. Commit changes
4. Settings > Pages > Branch: main, folder: / (root) > Save

## Future updates
Upload the new site.html only. Visitors see it immediately — no cache clearing needed.

## Source files (not needed by the website)
- source/Wedding.dc.html        editable source of the site
- source/Invitation.dc.html     Arabic wedding invitation card
- source/Lunch Invitation.dc.html   Arabic lunch invitation card
- source/support.js             runtime used by the source files
- source/assets/                photos, logo, and the exported invitation images
