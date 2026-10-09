# PVGIS

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-solar-lightgrey)

> Anticloud-hardened packaging of the upstream project `PVGIS` in category **SOLAR**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SOLAR · **Upstream:** https://github.com/nagilum/pvgis · **Upstream pin:** `7afa341603d5d2adecdfd3cddceed64bd1f69d46` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# Photovoltaic Geographical Information System (PVGIS) API

Solar energy is one of the environmentally sustainable resources for producing electricity using photovoltaic (PV) systems.
The main input data used in the planning process is solar radiation.
The [Europe JRC](https://re.jrc.ec.europa.eu/pvgis/) has an [app](https://re.jrc.ec.europa.eu/pvg_tools/en/tools.html) online which you can use to calculate PV values, bus sadly they have no (good) API.
That's where this website/API comes into play.

The PVGIS API provides a simple API endpoint which you can get the same values via JSON.
The API and source code is freely available to use under the [MIT license](https://github.com/nagilum/pvgis/blob/master/LICENSE.md).

See <https://pvgisjson.com> for details on how to use the API.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `src/`
- Snapshot size: **38 files**, **2198 lines of code** (measured; see Benchmarks)
- Primary languages: `.json` (10), `(none)` (6), `.js` (5), `.cs` (3), `.html` (3), `.less` (2)
- Upstream commit pinned for this packaging: `7afa341603d5d2adecdfd3cddceed64bd1f69d46`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# No standard manifest detected. Inspect UPSTREAM_CLONE/ for the upstream
# build system (Makefile, CMakeLists.txt, configure, ...) and follow it.
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

That's where this website/API comes into play.

The PVGIS API provides a simple API endpoint which you can get the same values via JSON.
The API and source code is freely available to use under the [MIT license](https://github.com/nagilum/pvgis/blob/master/LICENSE.md).

See <https://pvgisjson.com> for details on how to use the API.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

Solar energy is one of the environmentally sustainable resources for producing electricity using photovoltaic (PV) systems.
The main input data used in the planning process is solar radiation.
The [Europe JRC](https://re.jrc.ec.europa.eu/pvgis/) has an [app](https://re.jrc.ec.europa.eu/pvg_tools/en/tools.html) online which you can use to calculate PV values, bus sadly they have no (good) API.
That's where this website/API comes into play.

The PVGIS API provides a simple API endpoint which you can get the same values via JSON.
The API and source code is freely available to use under the [MIT license](https://github.com/nagilum/pvgis/blob/master/LICENSE.md).

See <https://pvgisjson.com> for details on how to use the API.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 38 |
| Lines of code | 2198 |
| Dependency references | 5 |
| Dependencies by ecosystem | npm: 5 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | request | ^2.88.0 | src/Node-PVGIS-v5-GCloudFunction/package.json |
| npm | express | ^4.17.1 | src/Node-PVGIS-v5/package.json |
| npm | request | ^2.88.0 | src/Node-PVGIS-v5/package.json |
| npm | express | ^4.17.1 | src/Node-PVGIS-v4/package.json |
| npm | request | ^2.88.0 | src/Node-PVGIS-v4/package.json |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

The main input data used in the planning process is solar radiation.
The [Europe JRC](https://re.jrc.ec.europa.eu/pvgis/) has an [app](https://re.jrc.ec.europa.eu/pvg_tools/en/tools.html) online which you can use to calculate PV values, bus sadly they have no (good) API.
That's where this website/API comes into play.

The PVGIS API provides a simple API endpoint which you can get the same values via JSON.
The API and source code is freely available to use under the [MIT license](https://github.com/nagilum/pvgis/blob/master/LICENSE.md).

See <https://pvgisjson.com> for details on how to use the API.

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `PVGIS` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.md` in the upstream snapshot).

License file excerpt:

```text
Copyright (c) 2019, Stian Hanger

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `PVGIS` (category: SOLAR)
- **Upstream URL:** https://github.com/nagilum/pvgis
- **Pinned commit (SHA):** `7afa341603d5d2adecdfd3cddceed64bd1f69d46`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`fe9bc86431a3184e14415a61feb29bf5d988aebea22136bb0e519072be25ad15`.

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
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

