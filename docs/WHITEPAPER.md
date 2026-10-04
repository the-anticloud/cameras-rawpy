# Technical Whitepaper — RAWPY

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/nicedoc/rawpy
**Category:** CAMERAS

## Abstract

This whitepaper describes the Anticloud integration of `RAWPY` (Python RAW image processing)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B on-device scene analysis — no cloud upload
2. AIOSS tamper-evident photo/video provenance chain (C2PA aligned)
3. AES-256 encryption for all stored media
4. Single-binary firmware with bundled local AI features
5. Zero-cloud: all scene recognition, auto-settings, and editing run on-device
6. GPU/CPU equalizer: uses camera ISP/NPU, falls back to main CPU
7. Zero-telemetry: removes all usage reporting to manufacturer
8. Open RAW processing pipeline replacing proprietary software

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.