# Pavithra & Isaac – Wedding Invitation

Files: index.html (content), style.css (look), script.js (date, maps, music), assets/ (photos, song.mp3)

## Edit details
- Names, message, verse, venues, times, parents, travel notes: search for "EDIT:" in index.html.
- Date, map links, music file name: top of script.js.
- Colours: top of style.css.

## Replace photos (keep the same file names, or change the names in index.html / style.css)
- assets/church.jpg         cover background, ceremony card background, church thumbnail (portrait)
- assets/church-inside.jpg  arch window behind the doors and on the first page (portrait)
- assets/lite.jpg           reception card background and location thumbnail
- assets/story.jpg          "Our Story" collage
- assets/portrait.jpg       couple photo above the countdown
- assets/couple.jpg, family.jpg   closing section photos
Resize to ~800-900px wide, JPG quality ~75, to keep it fast on phones.

## Add music
Put an mp3 named song.mp3 in assets/ (or change MUSIC_FILE in script.js). Keep it under ~3 MB. Music starts only when guests tap "Tap to Open". With no file, the music button stays hidden.

## Publish free on GitHub Pages
1. Create a free account at github.com and click New repository (name e.g. wedding-invite, Public).
2. Click "uploading an existing file", drag in index.html, style.css, script.js, README.md and the assets folder, then Commit.
3. Go to Settings > Pages. Under Build and deployment choose "Deploy from a branch", branch main, folder /(root), Save.
4. After 1-2 minutes your link is https://YOUR-USERNAME.github.io/wedding-invite/ . Share it on WhatsApp.
Test locally by double-clicking index.html (music needs the mp3 present).
