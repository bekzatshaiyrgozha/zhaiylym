# Zhaiylym: Open Pasture Map

Zhaiylym ("pasture" in Kazakh) is a proposed free, open source app that helps herding families plan grazing so degraded land can recover.

> **Project status: concept stage.** This repository holds the project's plan and governance documents. There is no application code yet, and every feature below is planned.

## The problem

Land around wells and villages can be overgrazed while more distant pastures stay unused. Herders need practical information about where and when to move animals, often in places with no mobile signal.

## SDG relevance

Zhaiylym addresses **SDG 15, Life on Land**, especially **target 15.3** on restoring degraded land and soil.

Planned measures of impact:

- number of pasture areas with a recorded rotation plan;
- vegetation change in those areas, measured from open satellite data;
- number of herding families using the plan each season.

## Planned features

- Offline maps and grazing plans stored on the phone
- Vegetation estimates from open Sentinel-2 satellite data
- Local observations from herders, shared only with consent
- Kazakh and Russian interface
- Herd locations shown only as anonymous areas

## Planned open technology

| Part | Planned choice | License |
| --- | --- | --- |
| Web app | React as a Progressive Web App | MIT |
| Maps | MapLibre GL JS | BSD-3-Clause |
| Base map data | OpenStreetMap | ODbL |
| Satellite data | Copernicus Sentinel-2 | Free and open data |
| API | FastAPI | MIT |
| Database | PostgreSQL with PostGIS | PostgreSQL License, GPL-2.0-or-later |

The app is planned to run in any modern browser, so it does not depend on one app store or operating system.

## Project documents

- [License](LICENSE): Apache License 2.0
- [Contributing guide](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Governance and ownership](GOVERNANCE.md)
- [Privacy and data plan](PRIVACY.md)

## AI use

Claude Code was used to help draft the structure and text of these documents.
