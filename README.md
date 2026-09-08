# EID — Electrical Impedance Discovery

Project preview. The source code has not yet been published.

EID — Electrical Impedance Discovery is a research-oriented software and hardware project for electrical bioimpedance measurement, data acquisition, and analysis.

EID is organized as a family of related components. Their maturity and integration status differ, and compatibility should be assessed using the documentation for each specific component and version.

## Components

| Component | Current status |
|---|---|
| Shared device API | Early-stage and partially implemented. Intended to define common device contracts and capability metadata. |
| Host API and Web GUI | Under active development. Supports host-side orchestration, browser-based interaction, and measurement-data handling. |
| Analog Discovery 2/3 driver | Under active development for measurement workflows using supported Analog Discovery hardware. |
| MAX30009/ESP32 path | A separate development path that is currently paused. It is not integrated with the common host or device API. |

## Current development priorities

- maintain clear and auditable architecture across the project family;
- improve AD2/AD3 device identification, export metadata, and multi-device operation;
- document software versions and hardware compatibility;
- continue research measurement and analysis activities;
- assess individual repositories for possible publication, including code, licensing, intellectual-property, dependency, and release review.

These priorities describe current planning and do not constitute a commitment to a particular release scope or schedule.

## Status and limitations

EID is presented solely as a research and engineering project. It is not presented as a medical device or as clinically validated, medically certified, regulatory-ready, or commercially ready. No future medical, clinical, regulatory, or commercial status is stated or implied.

This repository is an architectural preview. It does not contain the EID source implementation, validated clinical workflows, or a complete production release.
