# Candidate Campaign Audit

Campaign state: complete. Repository, artifact, print, confidentiality, interaction, deployment, and live-route gates passed.

## Factual integrity
- Candidate evidence is limited to the verified canonical record.
- Historical titles and dates are preserved.
- Concepts are not represented as production deployments.
- The platform-specific experience gap is stated directly.
- Public company signals are distinguished from candidate hypotheses.

## Brand fidelity
- Official Allstate hands mark: locally stored and visibly used.
- Color provenance: documented.
- Typography decision: documented; no proprietary font files.
- Independent-candidate distinction: explicit.

## UX and interaction
- Smart starting state: public human-verified claim-communication baseline.
- Scenario status labels: public baseline, public signal, or illustrative hypothesis.
- Meaningful participation: workload choice changes authority, controls, release posture, and trace requirements.
- Desktop, laptop, tablet, mobile, reduced-motion, keyboard, overflow, interaction, reset, and local-link checks passed.
- No fabricated progress, maturity score, target percentage, scarcity, countdown, or gated content.

## Artifact contracts
- Resume: exactly 2 pages.
- Cover letter: exactly 1 page.
- Interview thesis brief: exactly 4 pages.
- 120-day entry plan: exactly 3 pages.
- AI Action Trace Review: exactly 2 pages.
- Reciprocal resume / cover-letter navigation: present.
- PDF download controls: present for every print artifact.
- PDFs generated successfully, structurally checked, text-extracted, and visually inspected.

## Confidentiality and repository integrity
- Source, filenames, extracted PDF text, and PDF metadata were scanned for internal-only process names.
- Complete artifact manifest is committed to `main` through a reviewed pull request.
- Temporary installer payloads were removed before release.
- GitHub Pages deployment is isolated from campaign-generation plumbing.

## Live release verification
- Live URL: `https://russelldudek.github.io/allstate/`.
- Audited source commit: `c22cb78a5f7902e675e50509b2a6801d9bdd1958`.
- GitHub Actions audit run: `29425877857`.
- Fifteen published assets were fetched from GitHub Pages and matched the audited source byte-for-byte: six HTML routes, two stylesheets, one script, the official logo asset, and five PDFs.
- Live PDF page contracts passed at `2 / 1 / 4 / 3 / 2`.
- Live candidate-facing confidentiality scan returned zero prohibited-source matches.
