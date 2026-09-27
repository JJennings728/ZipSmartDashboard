# ZIPSmart Dashboard

**Portfolio context:** This repository is part of James Jennings' [Applied AI, Risk Analytics & Data Engineering portfolio](https://github.com/JJennings728/ZipSmart360/blob/main/PORTFOLIO.md).

The working dashboard is maintained with its data pipeline in **[JJennings728/ZipSmart360](https://github.com/JJennings728/ZipSmart360)**. This repository is a navigation page, not a separate application.

![Dashboard illustration](https://raw.githubusercontent.com/JJennings728/ZipSmart360/main/docs/dashboard-preview.svg)

## Run it locally

```bash
git clone https://github.com/JJennings728/ZipSmart360.git
cd ZipSmart360
python zipsmart.py
python server.py
```

Open http://127.0.0.1:8000. Or open `build/dashboard.html` directly after the build.

The dashboard supports state and ZIP-prefix filters, preserves leading-zero ZIP codes, and labels all figures as synthetic. The illustration above is not a browser screenshot. No production data, validated risk scores, or hosted service is represented.

[Source template](https://github.com/JJennings728/ZipSmart360/blob/main/web/dashboard.html) · [Saved HTML example](https://github.com/JJennings728/ZipSmart360/blob/main/examples/dashboard.html) · [Data dictionary](https://github.com/JJennings728/ZipSmart360/blob/main/docs/data-dictionary.md)
