# Arafah Khutbah 2026

Arabic text transcripts of the Arafah Khutbah.

## Data location (map)

```mermaid
flowchart TD
  R["repo root"] --> D["data/"]
  D --> Y["2026/"]
  Y --> L["ar/"]
  L --> RAW["raw.txt (no timestamps)"]
  L --> TS["timestamps.txt (with timestamps)"]
  R --> S["SOURCES.md (YouTube URLs + channels)"]
  R --> LIC["LICENSE (added by repo owner)"]
```

## Data layout (tree)

- `data/2026/ar/raw.txt`
- `data/2026/ar/timestamps.txt`
- `SOURCES.md`

## Sources / attribution

All source YouTube URLs and channel names should be recorded in `SOURCES.md`.

## How it was generated (accuracy note)

The transcript was generated using **OpenAI Whisper (medium)**. Expect occasional errors (spelling, mishearing, timestamp drift, or missing text). Fixes are welcome via issues or pull requests.

## No media in this repo

This repository is intended to contain **text transcripts only**. Do not upload audio/video files; see `.gitignore`.

## Licensing / rights (read this)

- The original **audio/video** remains owned by its rightsholder(s).
- A verbatim transcript may be considered a **derivative work** in some jurisdictions.
- Only apply a Creative Commons license to material you have rights/permission to license.

This repo expects you (the maintainer) to add the intended license file at `LICENSE` when you publish.

## File format

- Encoding: UTF-8
- `raw.txt`: plain Arabic text (may be a single long paragraph/line)
- `timestamps.txt`: one segment per line in this format:

`[MM:SS.mmm] --> [MM:SS.mmm]   Arabic text...`

Example:

`[00:23.000] --> [00:31.000]   السلام عليكم ورحمة الله وبركاته`
