# Bug-to-Proof demo recording

Bug-to-Proof is the project; **Proofline** is the dashboard.

## Actual dashboard recording — 23 October 2026

[Watch the Proofline dashboard demo](docs/evidence/portfolio/proofline-dashboard-demo.mp4)

This continuous browser recording shows the real case register, searching, opening the report dialog, typing structured details, saving a report through the local API, and opening a separate retained reference case to inspect evidence and the proof-download control. API responses and case statuses are not mocked. It has no audio. The saved report is a demo description of a seeded defect, not a newly verified bug. The later reference case uses a deterministic repair proposal; no live-model repair runs during this recording.

To record again on Windows, start the local apps with `npm run dev`, then run `npm run demo:dashboard`. Chromium and FFmpeg must be installed. The recorder creates a real local demo report. The evidence runner retains the exact executed spec, screenshots, raw WebM, traces, and result under `artifacts/dashboard-recording/`. The MP4 is saved in `docs/evidence/portfolio/`.

## Current reference walkthrough — 22 October 2026

[Watch the 36-second MP4](docs/evidence/portfolio/reference-walkthrough.mp4)

The video walks through real captured browser evidence: the seeded cart-total failure, the deterministic one-line patch, the identical test passing afterward, and proof verification. Captions identify the scripted approval and reference-proposal boundary. It is an edited evidence walkthrough without audio, rather than continuous screen capture or live-model repair.

[Evidence, before/after screenshots, and provenance](docs/evidence/portfolio-reference.md) · [Run the reference demo](docs/demo-script.md)

## Historical recording

The animation below shows an earlier configured MiniShop demo, not the current reference run or arbitrary report generation.

![Historical Bug-to-Proof demo](bug_to_proof_demo_1790517934780.webp)
