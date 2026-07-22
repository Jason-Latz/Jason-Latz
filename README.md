<!-- Profile README for Jason-Latz -->

<p align="center">
  <img src="https://github.com/user-attachments/assets/537fd42e-0906-4813-8dac-37ac2337df7c" alt="Jason watching a sunset over the lake" width="320" style="border-radius: 12px;" />
</p>

<h1 align="center">What's up? I’m Jason :) </h1>

<p align="center">
  <a href="https://github.com/Jason-Latz">
    <img src="https://img.shields.io/github/followers/Jason-Latz?label=Follow&style=social" alt="GitHub Followers" />
  </a>
  <a href="https://www.linkedin.com/in/jason-latz-7b8634242/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=flat" alt="LinkedIn" />
  </a>
</p>

---

## 🌟 About Me

I'm a Northwestern student studying Computer Science and Psychology! After working for a YC startup all winter, I'm just chilling and working on my own projects, mostly B2C stuff focusing on providing value to society! Health, education, and journaling are the focus areas I've been taking a look at recently. Have a look around!


---

## 🚀 Recent Work (Updated July 22, 2026)

- Between **July 14 and July 22, 2026**, I kept evolving [contexto](https://github.com/Jason-Latz/contexto): the extension now defaults to progressive on-demand tail loading with chunked manifests and incremental percolation, the mint queue got stronger evidence/ranking logic plus Wikipedia/Freedict inputs and stricter adjudication, I shipped the first panel-gated long-tail mint wave across French, Italian, German, and Spanish while documenting the proof shots and error rates, and then on **July 20** and **July 22** I hardened the mint pipeline so resume/panel state fails closed and every accepted word keeps its source-POS match and panel provenance.
- On **July 16, 2026**, I pushed another big [jasonlatz.com](https://github.com/Jason-Latz/jbl-site) pass: I introduced a shared "Reading Room" inner-page system and rebuilt `/writings`, `/experience`, `/photography`, `/travel`, and mobile `/summer-blog` around it, cut the homepage GLB from **29.3MB to 6.4MB** with an SSR poster/loading path, and then tuned the mobile desk experience with slimmer nav/HUD chrome, touch-first affordances, whole-desk framing, portrait posters, and sticky-header fixes.
- On **July 15, 2026**, I upgraded **Yapper** 🔒 with a more reviewable learning flow: sessions now persist as transcript threads in a new Journal tab, the live conversation renders chat-style as you speak, post-session recap sheets summarize difficult words and highlight exact corrections inline, and a follow-up polish pass tightened bubble layout, banner placement, and one-write turn persistence.
- On **July 15, 2026**, I hardened **Vinyl** 🔒's data-writing path: entry edits now go through targeted SQL-guarded updates instead of rewriting stale snapshots, detected-date/day-number/cloud-improve fields write independently, and the tracker-value source index widened to cover the `recorded_at` sort path.
- On **July 13, 2026**, I overhauled the writing flow on [jasonlatz.com](https://github.com/Jason-Latz/jbl-site): posts are now authored in a markdown-first editor with a read-only preview, a reusable `MarkdownEditor` component, and an editorial-serif reading/writing surface, plus regression-tested fixes for selection nesting, list continuation, link insertion, and preserving a post's original publish date.
- On **July 12, 2026**, I kept expanding [contexto](https://github.com/Jason-Latz/contexto): I ran a four-language audit/cleanup pass across German, French, Italian, and Spanish, added a live page-status/settings-sync flow that survives bfcache restores and late-loading content, and shipped a compact tuple-pack + tail-pack format that parses about 2x faster while shrinking the distributed packs by 72%.
- On **July 12, 2026**, I polished **Campaign Studio** 🔒 into a cleaner production surface: `tryj2.com` is now the canonical domain, the J² monogram replaced the older civic-star branding across the favicon/share card, the demo sites use real grouped campaign photos plus anonymized placeholder copy, and the team/contact surfaces got launch polish.
- On **July 8, 2026**, I ran a performance and reliability pass on **Vinyl** 🔒, my journaling app: I added an O(1) in-memory journaled-days index, new targeted indexes/queries for tracker values, debounced visibility-gated Insights recomputation, incremental alignment-sheet updates instead of full reloads, batch-scoped background import scheduling, and benchmark coverage to lock in the wins.
- On **July 8, 2026**, I did the same for **Yapper** 🔒, my on-device Spanish tutor: tutor replies now draft speculatively while endpointing finishes, the Foundation model/recognizer/TTS paths warm up and cache aggressively, the latency and regression corpus got much deeper coverage, and I added a guarded `ser`→`tener` age-correction rule to improve feedback precision.
- Between **June 17 and July 2, 2026**, I kept building out [jasonlatz.com](https://github.com/Jason-Latz/jbl-site): [PR #7](https://github.com/Jason-Latz/jbl-site/pull/7) gave the site an immersive full-bleed 3D homepage with a floating glass nav, split `/photography` into its own gallery, and turned `/travel` into a 3D globe of the places I've been; in early July I populated that globe with my real photos (an offline EXIF + StreetCLIP batch geolocates each shot, correctable from the admin panel), shipped an unlisted, passcode-gated `/summer-blog` weekly writing tracker, and [fixed a Spotify bug](https://github.com/Jason-Latz/jbl-site/pull/8) that showed a stale track as "now playing" after playback stopped.
- On **June 25, 2026**, I expanded my vocabulary-learning browser extension [contexto](https://github.com/Jason-Latz/contexto) from Spanish-only to four languages: I generated German, French, and Italian packs (50k+ entries each) from a new Wiktextract import pipeline, with per-language grammar adapters and a target-language picker, landing at 94–96% accuracy across all four (v0.2.0). Then on **July 1**, I added a lazy-loaded "tail" shard architecture that quarantines the niche long tail (es 88k · de 73k · fr 72k · it 69k) so it loads on demand without bloating the base packs.
- On **July 1, 2026**, I ran a design-refinement pass on my journaling app **Vinyl** 🔒, building a ledger-based visual language with surface-elevation tiers, a serif journal-page masthead, a focal Insights stat, and restrained haptics. Earlier, on **June 23**, I added voice-memo import (document picker into the on-device transcription pipeline) and framing-gated spoken-rating detection that reads a rating from what you say, hardened against false positives behind a provisional confirm banner.
- On **June 23, 2026**, I built a streak system for my on-device Spanish tutor **Yapper** 🔒: a Duolingo import flow that reads your streak with on-device Vision OCR (no network), an anti-cheat verifier hardened through adversarial review, an actor-backed StreakStore, and a Home streak card that only counts a day once you finish a turn.
- Across **June 17–20, 2026**, I shipped the "Aurea" redesign of **Audible Quizlet** 🔒, my audio-first flashcard app: I rebuilt it around a listening orb with semantic design tokens and dark mode, an off-main deck store with O(1) rendering, a debounced import parser, `@Observable` speech, and best-quality TTS voices with a picker, all verified by an end-to-end UI test and an adversarial review pass.
- On **June 16, 2026**, I got my on-device Spanish tutor **Yapper** 🔒 TestFlight-submission-ready (everything short of the credentialed Apple upload): [PR #6](https://github.com/Jason-Latz/yapper/pull/6) made the speech recognizer a pluggable backend (shipping on Apple's on-device STT, with NVIDIA Parakeet benchmarked, documented, and deferred behind the same seam), and [PR #7](https://github.com/Jason-Latz/yapper/pull/7) forced fully on-device recognition so the "100% on device" privacy claim is actually true, hardened the app against mid-session audio crashes and call/Siri interruptions, and wired up the App Store submission config.
- On **June 11, 2026**, I relaunched my personal site with ["The Desk"](https://github.com/Jason-Latz/jbl-site/pull/6): an interactive, lamplit 3D homepage where every object is live data and a doorway into the site (a turntable that plays what I'm actually listening to, my real bookshelf, a public guestbook notepad, and one persistent world-vs-Jason chess game), with a designed fallback for no-WebGL and reduced-motion visitors.
- On **June 10, 2026**, I ran parallel production-readiness pushes: **Vinyl** 🔒 [PR #15](https://github.com/Jason-Latz/vinyl/pull/15) and [PR #16](https://github.com/Jason-Latz/vinyl/pull/16) swept the app toward App Store submission (the spinning-record motif, recordings that survive auto-lock, privacy-manifest essentials, test suite from 19 to 59), while **Yapper** 🔒 [PR #4](https://github.com/Jason-Latz/yapper/pull/4) and [PR #5](https://github.com/Jason-Latz/yapper/pull/5) hardened the cross-stack contract and then moved the tutor entirely on-device (an Apple FoundationModels → heuristic engine ladder, local persistence, and zero network calls).

<sub>🔒 = private repo; any links here resolve once I open the source.</sub>

---

## 🧊 3D Contribution Graph
<p align="center">
  <img src="profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution graph" />
</p>

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="Python" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="TypeScript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="React" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="Node.js" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="Docker" />
</p>

---

## 📨 Contact Me
<p align="center">
  <a href="mailto:latz@u.northwestern.edu"><strong>Email</strong></a> •
  <a href="https://www.linkedin.com/in/jason-latz-7b8634242/"><strong>LinkedIn</strong></a>
</p>
