# Media for the website

Files put here show in the "See it" section of the website, above Download.
Missing files are skipped; with none the section stays hidden.

| File | What |
| --- | --- |
| `demo.mp4` | A short video of the show (H.264 mp4; best under 25 MB, the limit for uploading on github.com; 20-40 s at 1280x720 is plenty). Export video in the app makes one. |
| `demo.jpg` | Optional: the picture shown before the video plays (Capture in the app makes a PNG; save it as JPG). |
| `screenshot-1.png` ... `screenshot-6.png` | Screenshots, in this order. `screenshot-1.png` is captioned "Main window". |

To add or replace them on github.com: open this folder, **Add file > Upload
files**, drop the files (with exactly these names), **Commit changes**. The
website shows them a minute later.

Captions and other names: edit `DEMO_VIDEO`, `DEMO_POSTER` and `SCREENSHOTS`
near the top of the script in `index.html`.

A second demo can be on YouTube (videos too big for GitHub): set `LIVE_VIDEO`
near the top of the script in `index.html` to its link (e.g.
`https://youtu.be/AbCdEfGhIjK`) and `LIVE_NOTE` to its caption. The page
shows only its picture until it is clicked; where YouTube is blocked, a link.
