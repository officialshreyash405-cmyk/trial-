Ananya Birthday Website
========================

This is a private birthday-surprise website for Ananya from Shreyash.

How to use
----------
1. Keep the folder structure intact.
2. Open index.html in a browser.
3. Enter the birthday PIN: 0807

Important files
---------------
- gift/i17.png                         -> Ananya's hero/profile photo
- gift/*.jpg                           -> the supplied memory photos
- assets/aarzu-edit.mp4                -> keep the original Aarzu video here (the video itself is intentionally unchanged)
- assets/music.mp3 and other tracks   -> existing music files from the original full website
- assets/ananya-birthday-voice.m4a    -> Shreyash's NEW birthday voice note (to be added)

Photos
------
The website uses the supplied 15 memory photos. There is no requirement for exactly 96 photos; the memory system now loops through the photos that are actually provided.

Where to edit text/details
--------------------------
Open script.js and edit the CONFIG section at the top.
The birthday letter currently contains a placeholder for Shreyash's personal words.

Notes
-----
- The website is a local static HTML/CSS/JavaScript site.
- It does not need npm, React, a backend, or a database.
- The Aarzu video is not modified by this version.
- If music/video/voice assets are missing, the page can still open; add the original full website's assets folder when deploying.
