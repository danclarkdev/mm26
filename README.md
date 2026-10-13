# The Recollection Archive

A static eight-recording player for a murder mystery evening.

## Setup

1. Export eight ElevenLabs recordings as MP3 files.
2. Name them `fragment-1.mp3` through `fragment-8.mp3` and put them in `audio/`.
3. In `index.html`, edit the `recollections` object to change titles, descriptions, numbers and file paths.
4. Create a public GitHub repository (e.g. `nicola-recollections`) and upload `index.html` and the `audio` folder.
5. In the repository, open **Settings > Pages**. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
6. Once GitHub Pages is published, your page will be at `https://YOUR-USERNAME.github.io/nicola-recollections/` (unless using a custom domain).
7. Create eight QR codes using these URLs, replacing the base URL:
   - `https://YOUR-USERNAME.github.io/nicola-recollections/?fragment=1`
   - `https://YOUR-USERNAME.github.io/nicola-recollections/?fragment=2`
   - ...through `?fragment=8`.
8. Print one QR code inside each sealed envelope.

## Important

- The archive is **public**. Unique QR URLs are not a security mechanism. Guests can change the URL to visit another fragment. Ask them to use only their own QR, or host the audio another way if access control matters.
- The memory number appears **only after the audio finishes**, but this is a theatrical reveal, not tamper-proof protection.
- Do not scan the QR codes during setup and accidentally spoil the recordings for your guests.
- Test all eight QR codes on a mobile phone before the event.
- The page needs internet access and an MP3 for each fragment. There are no placeholder audio recordings included.
- Fonts are loaded from Google Fonts; if unavailable, fallback fonts will display.
