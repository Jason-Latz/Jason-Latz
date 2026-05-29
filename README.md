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

## 🚀 Recent Work (Updated May 29, 2026)

- On **May 29, 2026**, I landed a batch of [vinyl](https://github.com/Jason-Latz/vinyl) performance fixes in [PR #4](https://github.com/Jason-Latz/vinyl/pull/4), [PR #5](https://github.com/Jason-Latz/vinyl/pull/5), [PR #6](https://github.com/Jason-Latz/vinyl/pull/6), and [PR #7](https://github.com/Jason-Latz/vinyl/pull/7): trimming the on-device analysis hot path, skipping a redundant Today recents reload after save, adding a composite Insights index for top-term queries, and bounding Library search previews so search results stop hauling full transcripts into Swift state.
- Also on **May 29, 2026**, I merged two other public cleanup/performance fixes: [LessonForge PR #2](https://github.com/Jason-Latz/LessonForge/pull/2), which memoizes repeated server-side lesson and creator reads during a render, and [yapper PR #2](https://github.com/Jason-Latz/yapper/pull/2) plus [PR #1](https://github.com/Jason-Latz/yapper/pull/1), which cut redundant live-session timer publishes and fixed iOS build Ruby-version detection in CI.
- On **May 28, 2026**, I opened draft private PR [#10](https://github.com/Jason-Latz/Kindle_pdf_translation/pull/10) for [Kindle_pdf_translation](https://github.com/Jason-Latz/Kindle_pdf_translation), avoiding PDF upload buffer copies by keeping `Buffer` input as a shared `Uint8Array` view through parsing, with regression coverage and docs after benchmarking the peak-memory drop.

- On **May 27, 2026**, I opened draft PR [#14](https://github.com/Jason-Latz/vinyl/pull/14) for [vinyl](https://github.com/Jason-Latz/vinyl), skipping redundant Library transcript searches when whitespace-only edits don’t change the normalized query, preserving forced refreshes when the screen reloads with an active search, and adding targeted view-model regression coverage plus a short behavior note.
- Earlier on **May 27, 2026**, I opened draft PR [#1](https://github.com/Jason-Latz/BioBeat/pull/1) for [BioBeat](https://github.com/Jason-Latz/BioBeat) to ignore generated session-label CSVs so normal self-training collector runs stop dirtying the repo while keeping the checked-in demo fixtures visible to Git.
- On **May 26, 2026**, I pushed another public [BioBeat](https://github.com/Jason-Latz/BioBeat) sprint that moved the prototype toward guided self-training: an Arduino-backed collector, synchronized song playback and sensor capture, a flicker-free countdown, auto-saved forward rating flow, and broader genre-diverse training clips and audio features across lo-fi, EDM, jazz, and country.
- Also on **May 26, 2026**, I opened draft PR [#9](https://github.com/Jason-Latz/Kindle_pdf_translation/pull/9) for [Kindle_pdf_translation](https://github.com/Jason-Latz/Kindle_pdf_translation), pausing hidden-tab `/api/jobs/:id` polling, forcing one immediate refresh when the page becomes visible again, and adding focused tests plus docs for the polling rule.
- On **May 25, 2026**, I pushed a first public [BioBeat](https://github.com/Jason-Latz/BioBeat) buildout: a Streamlit replay dashboard, iTunes preview-clip selection, audio-feature extraction and normalization, synthetic biometric generation, baseline model training and metrics, and recommendation ranking for a mood-based music prototype.
- Earlier on **May 25, 2026**, I opened two draft private PRs: one cuts peak memory on a voice-journaling save path by streaming large audio files through chunked SHA-256 checksums with regression coverage, and the other restores a missing console-script entrypoint for a CLI experiment seed while replaying its scoring, planning, rendering, and sample-artifact stack onto a clean branch.
- On **May 24, 2026**, I opened a draft private iOS insights-performance PR that caches one computed snapshot per time window, avoids rerunning top-term aggregation and chart reshaping when I revisit an already loaded range, adds focused regression coverage, and documents the one-load-cycle cache rule.
- Also on **May 24, 2026**, I opened a draft private CLI-seed packaging PR that restores a missing installed console script, keeps the fix scoped to packaging, and validates the markdown and JSON sample-output path end to end.
- On **May 23, 2026**, I opened a draft private optimization PR that reuses one shared score snapshot while compiling a state vector, removes duplicate scorer work from the hot path, adds regression coverage, and documents the single-pass scoring rule.
- Also on **May 23, 2026**, I turned another private CLI seed into a draft PR by wiring its missing installed console script, then validated the editable-install path alongside the markdown and JSON sample outputs it produces.
- On **May 22, 2026**, I opened a draft private iOS journaling performance PR that replaces a recursive storage-size file walk with metadata-backed byte summing plus direct SQLite artifact stats, adds focused regression coverage, and documents the cheaper Settings read path.
- Also on **May 22, 2026**, I packaged a private experimental seed into a draft PR around scenario scoring, response-lane planning, markdown and JSON brief rendering, sample artifacts, and the console script wiring needed for clean editable installs.
- On **May 21, 2026**, I opened a draft private iOS journaling cleanup PR that projects only stored audio paths before delete-one and delete-all flows, trims unnecessary decoding from the cleanup hot path, adds regression coverage, and documents the database-performance rule behind the change.
- Also on **May 21, 2026**, I packaged a private CLI experiment into a draft PR around interruption triage: scenario scoring, response-lane planning, markdown and JSON brief rendering, sample artifacts, and the missing installed console script needed for clean editable installs.
- On **May 20, 2026**, I opened a draft private iOS journaling pipeline PR that reuses cloud-improved transcript text already in memory during analysis, removes a redundant database fetch from the processing hot path, adds regression coverage, and tightens the pipeline docs.
- On **May 19, 2026**, I opened a draft private data-layer PR that collapses active-transcript lookups into a single joined GRDB read, adds coverage for multi-version transcript selection, and documents the local transcription and analysis database path.
- On **May 18, 2026**, I merged [Pencil PR #14](https://github.com/kev1n/pencil/pull/14), fixing a subtle CTEC professor-matching bug so classes taught by instructors who share a last name no longer pull the wrong analytics, including the paper.nu schedule-card path that only showed abbreviated names.
- Also on **May 18, 2026**, I merged a [Pencil landing page refresh](https://github.com/kev1n/pencil-landing-page/pull/3) that synced the site copy with the extension changelog, tightened the CTA and footer polish, and clarified the privacy / CAESAR-gating story around the product rollout.
- Across **May 13-16, 2026**, I shipped a dense run of [Pencil](https://github.com/kev1n/pencil) improvements in [PR #3](https://github.com/kev1n/pencil/pull/3), [PR #6](https://github.com/kev1n/pencil/pull/6), [PR #7](https://github.com/kev1n/pencil/pull/7), [PR #8](https://github.com/kev1n/pencil/pull/8), [PR #9](https://github.com/kev1n/pencil/pull/9), [PR #10](https://github.com/kev1n/pencil/pull/10), [PR #11](https://github.com/kev1n/pencil/pull/11), [PR #12](https://github.com/kev1n/pencil/pull/12), and [PR #13](https://github.com/kev1n/pencil/pull/13): compact class-search section lists, lazy schedule-combination controls, paper.nu export/help flows, CTEC and study-load UX polish, and a handful of layout and teardown fixes.

---

## 📌 Recent GitHub Activity
<!--RECENT_ACTIVITY:start-->
<!--RECENT_ACTIVITY:end-->

---

## 🧮 My GitHub Metrics
<p align="center">
  <img src="profile-3d-contrib/profile-night-rainbow.svg" alt="GitHub metrics" style="border-radius: 10px; box-shadow: 0px 4px 12px rgba(0,0,0,0.15);" />
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
