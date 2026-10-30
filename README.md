# The Aisha Dispatch | Birthday Special Report

A one-page, six-page interactive noir newspaper created as a birthday surprise for Aisha. It starts with a dramatic, entirely fictional news investigation, lets readers examine two original video recordings, and ends with a sincere birthday note from a close friend.

## Open it

1. Extract the complete ZIP, keeping all files together.
2. Open `index.html` in Chrome, Safari, Edge, or Firefox.
3. Press **Read the Special Report** to enter. This deliberate tap also authorises the soundtrack on compatible browsers.
4. Turn pages with the arrows, swipes on touchscreens, or keyboard arrow keys.
5. On the evidence page, choose **Watch clip 01** or **Watch clip 02** to view Aisha's original videos upright. Close the footage to return to the newspaper.

The experience is static and does not require npm, a build system, an API, or a server. Some browsers restrict `file://` media playback. If you encounter this, host the folder on a static site or run a local HTTP server (`python -m http.server 8000`) and open `http://localhost:8000` instead.

## What's included

- `index.html`: responsive newspaper experience, styles, transitions, keyboard and touch interactions, audio and modal playback logic.
- `exhibit-a.png`: Aisha's first supplied photo, rotated upright and lightly adjusted.
- `exhibit-b.png`: Aisha's second supplied photo, rotated upright and lightly adjusted.
- `exhibit-c.png`: still from the supplied second recording, rotated upright.
- `footage-01.mp4` and `footage-02.mp4`: both original video recordings, rotated upright and encoded as H.264 MP4 for broad compatibility.
- `theme.mp3`: the original project's soundtrack (unchanged).
- `vercel.json`: original static-hosting configuration (unchanged).

## Publish to Vercel

Upload the contents of this folder to a GitHub repository root, then import it into Vercel. Leave the framework preset as **Other**, with no build command. Do not upload this as a React project; it is a complete static page.

## Mobile and desktop

The existing project supports a single-page mobile newspaper, a two-page desktop spread, swipe and keyboard navigation, safe-area insets, portrait and landscape phones, tall content scrolling, a music toggle, and reduced-motion preferences. The footage viewer has an explicit close button and supports Escape on desktop. Videos play only on request and pause the background theme while open.

## Privacy and tone

This is a personal birthday surprise. The 'charges' and investigation are entirely fictitious jokes. The page includes a `noindex` robots directive to discourage search indexing, but that **does not make the page private**. Share the deployed URL only with people Aisha would be comfortable showing her photos and videos to. Use password-protected hosting if privacy is important.
