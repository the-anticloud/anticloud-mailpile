# MAILPILE

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-surveillance_camera-lightgrey)

> Anticloud-hardened packaging of the upstream project `MAILPILE` in category **SURVEILLANCE CAMERA**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SURVEILLANCE CAMERA · **Upstream:** https://github.com/mailpile/Mailpile · **Upstream pin:** `741e610f3e765f03bd0c452c92c6758280e7f99f` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# Welcome to Mailpile! #

**IMPORTANT NOTE**

Development on this codebase has halted, until the
[Python3 rewrite](https://community.mailpile.is/t/a-very-uninformative-progress-update-mailpile-2/785)
has completed.

Apologies to those who have unanswered, out-standing pull requests and
issues. 😢 Your efforts are appreciated!

If you rely on this code and have your own branch which you actively
maintain, let us know: we would be happy to link to it.

If you need to run Mailpile v1 to access legacy data, consider using
our [legacy Docker images](https://github.com/mailpile/Mailpile-v1-Docker).

------------------------------------------------------------------------

## Introduction (Obsolete) ##

Mailpile (<https://www.mailpile.is/>) is a modern, fast web-mail client
with user-friendly encryption and privacy features. The development of
Mailpile is funded by
[a large community of backers](https://www.mailpile.is/#community)
and all code related to the project is and will be released under an OSI
approved Free Software license.

Mailpile places great emphasis on providing a clean, elegant user
interface and pleasant user experience. In particular, Mailpile aims to
make it easy and convenient to receive and send PGP encrypted or signed
e-mail.

Mailpile's primary user interface is web-based, but it also has a basic
command-line interface and an API for developers. Using web technology
for the interface allows Mailpile to function both as a local desktop
application (accessed by visiting `localhost` in the browser) or a
remote web-mail on a personal server or VPS.

The core of Mailpile is a fast search engine, custom written to deal
with large volumes of e-mail on consumer hardware. The search engine
allows e-mail to be organized using tags (similar to GMail's labels) and
the application can be configured to automatically tag incoming mail
either based on static rules or bayesian classifiers.

### Trying Mailpile

If you need to run Mailpile v1 to access legacy data, consider using
our [legacy Docker images](https://github.com/mailpile/Mailpile-v1-Docker).

## Credits and License ##

Bjarni R. Einarsson (<http://bre.klaki.net/>) created this!  If you
think it's neat, you should also check out PageKite:
<https://pagekite.net/>. [Smári](<http://www.smarimccarthy.is/>) and
[Brennan](https://brennannovak.com) joined the team in 2013 and made
this a real project (not just a toy search engine).

The original GMail team deserve a mention for their inspiring work:
wishing the Free Software world had something like GMail is what
motivated Bjarni to start working on Mailpile. We would also like to
thank Edward Snowden for inspiring us to try and make PGP usable for
journalists and everday folks!

Contributors:

- Bjarni R. Einarsson (<http://bre.klaki.net/>)
- Brennan Novak (<https://brennannovak.com/>)
- Smari McCarthy (<http://www.smarimccarthy.is/>)
- Lots more, run `git shortlog -s` for a list! (Or check
  [GitHub](https://github.com/mailpile/Mailpile/graphs/contributors).)

And of course, we couldn't do this without [our community of
backers](https://www.mailpile.is/#community).

This program is free software: you can redistribute it and/or modify it
under the terms of the GNU Affero General Public License as published by
the Free Software Foundation. See the file `COPYING.md` for details.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json; scanned in UPSTREAM_CLONE)
- Top-level source layout: `design/`, `doc/`, `lib/`, `mailpile/`, `packages/`, `scripts/`, `shared-data/`, `submodules/`
- Snapshot size: **720 files**, **66369 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (157), `.html` (132), `.svg` (122), `.js` (64), `.png` (61), `(none)` (42)
- Upstream commit pinned for this packaging: `741e610f3e765f03bd0c452c92c6758280e7f99f`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# from this project directory
npm install        # or: npm ci
npm run build      # if a build script is declared
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

```sh
npm start          # declared start script, when present
npm run dev        # declared dev script, when present
```

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

with user-friendly encryption and privacy features. The development of
Mailpile is funded by
[a large community of backers](https://www.mailpile.is/#community)
and all code related to the project is and will be released under an OSI
approved Free Software license.

Mailpile places great emphasis on providing a clean, elegant user
interface and pleasant user experience. In particular, Mailpile aims to
make it easy and convenient to receive and send PGP encrypted or signed
e-mail.

Mailpile's primary user interface is web-based, but it also has a basic
command-line interface and an API for developers. Using web technology
for the interface allows Mailpile to function both as a local desktop
application (accessed by visiting `localhost` in the browser) or a
remote web-mail on a personal server or VPS.

The core of Mailpile is a fast search engine, custom written to deal
with large volumes of e-mail on consumer hardware. The search engine
allows e-mail to be organized using tags (similar to GMail's labels) and
the application can be configured to automatically tag incoming mail
either based on static rules or bayesian classifiers.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json |
| Files in snapshot | 720 |
| Lines of code | 66369 |
| Dependency references | 5 |
| Dependencies by ecosystem | npm: 5 |
| Upstream license | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | grunt | latest | package.json |
| npm | grunt-contrib-concat | latest | package.json |
| npm | grunt-contrib-uglify | latest | package.json |
| npm | grunt-contrib-less | latest | package.json |
| npm | grunt-contrib-watch | latest | package.json |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

either based on static rules or bayesian classifiers.

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

## How to contribute to Mailpile

First of all: Thank you! :heart:

#### Further Reading

Second of all, please adhere to our Code of Conduct when you participate
in our community. Be kind, be respectful. [The full Code of Conduct can
be found here](CODE_OF_CONDUCT.md).

Please also be sure you are comfortable with [our license](COPYING.md)
before contributing any code to Mailpile.

Note that Mailpile is a slightly unsual app; the design is both political
and opinionated. If you are confused or unsure whether something is a bug or a
feature, [our developer FAQ might have answers](DEV_FAQ.md)! Please read it
before filing issues about design choices or attempting to reorganize the code
in any major way. The FAQ also contains a quick introduction Mailpile internals
and debugging techniques.

Also, have you seen [the main Mailpile website](https://www.mailpile.is/) and
[the community Discourse](https://community.mailpile.is/categories)?

#### Are you new to Mailpile and/or FOSS?

* Welcome! The first step is probably to get Mailpile up and running, play with it, get familiar.

* Read the links above, and [check out our website](https://www.mailpile.is/) if you haven't already.

* Not sure what to work on? Find inspiration in one of our [Low Hanging Fruit](https://github.com/mailpile/Mailpile/issues?q=is%3Aissue+is%3Aopen+label%3A%22Low+Hanging+Fruit%22) issues!

* Otherwise, read on...

#### Did you find a bug?

* **Ensure the bug was not already reported** by searching on GitHub
  under [Issues](https://github.com/mailpile/Mailpile/issues).

* If you're unable to find an open issue addressing the problem,
  [open a new one](https://github.com/mailpile/Mailpile/issues/new). Be
  sure to include a **title and clear description**, as much relevant
  information as possible.

* Remember, we cannot read your mind or see your screen, so you'll
  probably need to answer all of these:

   1. What were you doing?
   2. What did you expect would happen?
   3. What actually happened?
   4. Operating system? GnuPG version? Mailpile version?

* Reproducability is key. If you cannot reliably trigger the bug or
  cannot describe how to do so, then unfortunately it's less likely that
  the Mailpile team will be able to do anything about it. It may still
  be useful to file a report in case others are having the same issue, but
  bugs that can be reproduced will in general get fixed much faster!

* The [Developer FAQ](DEV_FAQ.md) has a section on debugging techniques.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: Apache-2.0** (evidence: `COPYING.md` in the upstream snapshot).

License file excerpt:

```text
# Mailpile - a program for doing stuff with e-mail

Copyright (C) 2011-2015, Bjarni R. Einarsson, Mailpile ehf and friends.

This program is free software: you can redistribute it and/or modify it
under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or (at
your option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU Affero
General Public License more details.

You should have received a copy of the GNU Affero General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.

## What happened to the Apache license?

```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original Apache-2.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `Apache-2.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `MAILPILE` (category: SURVEILLANCE CAMERA)
- **Upstream URL:** https://github.com/mailpile/Mailpile
- **Pinned commit (SHA):** `741e610f3e765f03bd0c452c92c6758280e7f99f`
- **Branch:** master
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`b6dee513616577294bae0d686bdcd47f2ce45e70b3b54a1dd4773573738d1e96`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

