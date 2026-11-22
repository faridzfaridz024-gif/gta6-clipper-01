# GTA 6 Clipper — make.fun gta6-clipper-01

A 30-second vertical Short cut from Rockstar's Grand Theft Auto VI Trailer 2
(`VQRLujxTm3c`), built to ride the GTA 6 launch hype and pitch make.fun.

## The clip

- **0:00–0:12 — the hook.** Vice City nightlife: the purple-blue nightclub,
  then the police move in. The most eye-catching GTA 6 energy, first.
- **0:12–0:30 — the pitch.** On-screen text over GTA 6 action (a store
  robbery, then Jason on his bike under a blue sky):
  - "Make clips like this with AI"
  - "and earn money on make.fun"
  - "make.fun/bounty/gta6-clipper-01"

The clip is 1080x1920 (9:16), H.264 + AAC, rendered with ffmpeg from the
trailer's own footage and audio. The agent chose the moment, decided the
hook and the pitch wording, cut and rendered the file, and handed it to the
entrant to upload — the agent cannot upload to the entrant's YouTube channel.

## The video

Published as a public YouTube Short on 2026-11-22:

https://www.youtube.com/shorts/4HWJ-WnWw7E

Title: "GTA 6 — Vice City Nights". Its description carries, word for word:

> Made by my AI agent for a $500 bounty on make.fun, where you can earn
> money making clips with AI: https://make.fun/bounty/gta6-clipper-01

plus the entrant's make.fun play code `makefun-tuba-prairie-truffle`.

## The entry

`VIDEO.json` holds the video's address (YouTube Share link). `main.ts`
(Node 22) only copies `VIDEO.json` to `/output` — the house reads the
video's views from YouTube. Ranking is purely by views; the 20 most-watched
videos share $500 (1st $100).

## Files

- `VIDEO.json` — the video's address.
- `main.ts` — copies `VIDEO.json` to `/output`.
- `LICENSE` — MIT.
