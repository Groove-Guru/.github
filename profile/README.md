<p align="center">
  <img src="https://raw.githubusercontent.com/Groove-Guru/.github/main/assets/readme-banner.png" alt="groove guru. hear your mix before the room does." width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-FF4A2B?style=for-the-badge&labelColor=0B0B0B" alt="Status: in development">
  <img src="https://img.shields.io/badge/HARNESS-RUST%20%C2%B7%20MIT-F2F0EA?style=for-the-badge&labelColor=0B0B0B" alt="Harness: Rust, MIT">
  <img src="https://img.shields.io/badge/NEEDS-PRO%20DJ%20LINK%20GEAR-A19E97?style=for-the-badge&labelColor=0B0B0B" alt="Needs Pro DJ Link gear">
</p>

<p align="center">
  <a href="https://groove.guru"><b>site</b></a> ·
  <a href="https://groove.guru/#step-1">try the drills</a> ·
  <a href="https://groove.guru/llms.txt">llms.txt</a>
</p>

---

**Groove Guru is a DJ tutor for Pioneer Pro DJ Link gear.** A small harness on the booth LAN
listens to your CDJs and mixer, mirrors the decks in your browser, and tells you, in a calm
voice, when the mix drifts: a Camelot clash, a blend that misses the phrase, a deck sliding
off the grid. Then it gets out of the way.

> Practice like someone is watching. Because something is.

## Where it stands

Nothing is released yet. What exists today and what doesn't:

| | What it is | Status |
| :--- | :--- | :--- |
| **Site** | The landing page and six drill previews that run in the browser: count the bar, cue on the one, ride the phrase, blend on Camelot, the first mix | **Live** |
| **Booth harness** | One Rust binary on a machine on the booth switch. Listens on UDP 50000–50002, never sends control. Open source, MIT | **In development** |
| **Coach** | Spoken notes on key, phrase and timing, one at a time | **In development** |
| **Pro** | Hosted sessions and history on Cloudflare. $6.99/mo or $49.99/yr at launch | **Planned** |
| **Companion** | iPad/iPhone glance view, over local Wi-Fi or Cloudflare | **Planned** |

## What it does not do

- It does not touch your mix. The harness is passive: it never sends control and never ducks the music.
- It does not work without gear. The drills on the site are a preview; the real path runs against live deck state.
- It is not a Pioneer product. Pioneer DJ and Pro DJ Link are trademarks of their respective owners; Groove Guru is independent and unaffiliated.

## Repositories

| Repo | What |
| :--- | :--- |
| [`website`](https://github.com/Groove-Guru/website) | The landing site. Static HTML, one CSS, one JS, Cloudflare Pages |
| `groove-guru` | The plan, then the harness. Private until the harness is released |
