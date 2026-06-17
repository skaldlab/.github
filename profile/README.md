<div align="center">

# 🐦‍⬛ Skald Lab

### Security tooling that fits how teams already ship.

We build open-source security tools for the modern GitHub workflow —
broad coverage, no per-seat pricing, and nothing leaves your repo.

[Website](https://skaldlab.dev) ·
[Muninn](https://github.com/skaldlab/muninn) ·
[Marketplace](https://github.com/marketplace/actions/muninn-security-scanner) ·
[@skaldlab](https://x.com/skaldlab)

</div>

---

## Our work

### 🐦‍⬛ [Muninn](https://github.com/skaldlab/muninn) — all-in-one CI/CD security scanner

[![CI](https://github.com/skaldlab/muninn/actions/workflows/ci.yml/badge.svg)](https://github.com/skaldlab/muninn/actions/workflows/ci.yml)
[![CodeQL](https://github.com/skaldlab/muninn/actions/workflows/codeql.yml/badge.svg)](https://github.com/skaldlab/muninn/actions/workflows/codeql.yml)
[![Release](https://badgen.net/github/release/skaldlab/muninn)](https://github.com/skaldlab/muninn/releases)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Marketplace](https://img.shields.io/badge/Marketplace-Muninn-181717?logo=github)](https://github.com/marketplace/actions/muninn-security-scanner)

One GitHub Action orchestrates eight best-in-class open-source scanners —
**gitleaks, zizmor, actionlint, poutine, semgrep, osv-scanner, trivy, checkov** —
normalizes their output into a single finding schema, and reports back as
PR comments, SARIF, or JSON.

```yaml
- uses: skaldlab/muninn@v0.3.3
  with:
    token: ${{ secrets.GITHUB_TOKEN }}
```

Secrets · SAST · CI/CD pipeline security · supply chain · dependencies · containers · IaC — in one line.

---

## Why we build this way

- **Open source first** — AGPL-3.0 core, self-hostable, trust through transparency.
- **Your code stays put** — scans run on your own runner; nothing is uploaded to us.
- **CI/CD-native** — built for GitHub Actions, results land in the Security tab automatically.
- **Zero config to start** — works out of the box, tune it later when you want to.

## The name

In Norse myth, a *skald* was a poet who kept and retold the stories that mattered.
**Muninn** ("Memory") was one of Odin's two ravens, sent out each day to observe the
world and return with what it learned. Our tools are named in that spirit — they watch,
remember, and report back.

## Get in touch

- General: **hello@skaldlab.dev**
- Security disclosures: **security@skaldlab.dev** (please don't open public issues)

<div align="center">
<sub>Made in Montevideo 🇺🇾 · AGPL-3.0 · Named after Odin's raven of Memory</sub>
</div>
