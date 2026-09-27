# ZIPSmart Dashboard

**Interactive reporting layer for the ZIPSmart360 data-engineering demonstration.**

[Working project](https://github.com/JJennings728/ZipSmart360) · [Dashboard source](https://github.com/JJennings728/ZipSmart360/blob/main/web/dashboard.html) · [Portfolio](https://github.com/JJennings728/ZipSmart360/blob/main/PORTFOLIO.md)

## Overview

This repository serves as the dashboard entry point for ZIPSmart360.

The active dashboard is maintained with the underlying pipeline in [JJennings728/ZipSmart360](https://github.com/JJennings728/ZipSmart360), keeping data generation, validation, API behavior, and presentation logic aligned in one executable project.

![ZIPSmart dashboard preview](https://raw.githubusercontent.com/JJennings728/ZipSmart360/main/docs/dashboard-preview.svg)

## Dashboard capabilities

The demonstration interface supports:

- state filtering;
- ZIP-prefix filtering;
- preservation of leading-zero ZIP identifiers;
- responsive tabular presentation;
- explicit synthetic-data labeling; and
- offline use after the build is generated.

## Run locally

```bash
git clone https://github.com/JJennings728/ZipSmart360.git
cd ZipSmart360

python zipsmart.py
python server.py
```

Open:

```text
http://127.0.0.1:8000
```

Or open the generated `build/dashboard.html` directly.

## Design principle

The dashboard is intentionally downstream of the validation and storage layers.

The presentation layer does not define analytical truth; it displays records that have already passed the pipeline's validation and transformation rules. This keeps data-quality controls separate from visualization logic.

## Status

This repository is a **navigation and presentation repository**, not a separately deployed application.

The dashboard uses synthetic data and does not represent a production risk score, insurer system, or hosted commercial service.

## Related artifacts

- [ZIPSmart360 source](https://github.com/JJennings728/ZipSmart360)
- [Architecture](https://github.com/JJennings728/ZipSmart360/blob/main/docs/architecture.md)
- [Data dictionary](https://github.com/JJennings728/ZipSmart360/blob/main/docs/data-dictionary.md)
- [Saved example output](https://github.com/JJennings728/ZipSmart360/blob/main/examples/dashboard.html)

## Author

**James Jennings**  
Applied AI · Risk Analytics · Data Engineering · Insurance

[LinkedIn](https://www.linkedin.com/in/james-jennings-2053b4a8) · [GitHub](https://github.com/JJennings728)
