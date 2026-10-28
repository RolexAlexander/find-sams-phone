# Find Sam's Phone

A one-minute classroom game for the CSE4101 *Local Search* segment (Group A).

Sam dropped his phone in a giant maze. Players can't see it, but the ringtone gets **louder** as they get closer, and a meter at the top shows whether each step made it louder or quieter. Finding the phone gives the group a code to type in the chat.

It is local search in disguise:

| Game | Local search |
|---|---|
| Where you stand | State |
| The squares next to you | Neighbours |
| How loud the ringtone is | Objective function |
| Step towards louder, repeat | Hill climbing / local search loop |

Play: open `index.html`, or the GitHub Pages site once it's enabled. Works on phones (buttons or swipe) and laptops (arrow keys / WASD). No install, no tracking, no network calls.

Codes look like `C-07-A76K` (group C, found in 7 s) or `C-X84-…` (time ran out, loudest point 84 %). Lower time wins.
