# Sherlock Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Sherlock cookbook** for username presence checks across public sites. Patterns are drawn from the ZQM fleet's Sherlock 0.16.2 installs (version-verified). The first live demo needs a named in-scope username — an owner decision, not something this cookbook assumes. It is intended for OSINT practitioners who check username presence across public platforms. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Sherlock patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. Intended to provide geospatial data feeds (POI, weather, satellite imagery, geocoding) for the ZQM game platform. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

OSINT practitioners who check username presence across public platforms.

## Prerequisites

- Sherlock 0.16.2
- Python 3.11+
- A username you own or are authorized to research

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-check` | A first username check and how to read its output |
| 02 | `02-site-lists` | Choosing and curating site lists |
| 03 | `03-output` | Exporting and filtering results |

## Repository layout

```text
sherlock-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [maigret-cookbook](https://github.com/ZQM-Computing/maigret-cookbook) — Username search with extended site coverage and reporting
- [theharvester-cookbook](https://github.com/ZQM-Computing/theharvester-cookbook) — Passive reconnaissance: domains, emails, and hosts from public sources
- [spiderfoot-cookbook](https://github.com/ZQM-Computing/spiderfoot-cookbook) — Passive OSINT automation as a service
