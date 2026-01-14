[![WarpedWing Labs](https://raw.githubusercontent.com/WarpedWing/WarpedWing/refs/heads/main/WarpedWingLabs_Logo_800x300.png)](https://github.com/WarpedWing/)

Passionate about the art and science of digital forensics.

[noel@warpedwinglabs.com](mailto:noel@warpedwinglabs.com)
<br/>

# Recent Projects

## MARS: macOS Artifact Recovery Suite

[![MARS](https://img.youtube.com/vi/YKRyHVraYgI/0.jpg)](https://www.youtube.com/watch?v=YKRyHVraYgI)

**MARS** is a data extraction and recovery toolkit for macOS that salvages and recovers SQLite, plist, log, and cache data from a set of raw, carved files and matches them with artifacts of forensic interest from a reference system.

In some cases, **MARS can recover thousands more database rows and hundreds of extra days of data beyond what exists in the original reference files alone.**

## Additional Features

- Easily mount EWF images directly in macOS via [FUSE-T](https://www.fuse-t.org/)
  - *(Completely avoids kernel-level FUSE install)*
- Automatic pseudo-logarchive creation, ready for [Unified Logs](https://github.com/mandiant/macos-UnifiedLogs) parsing
- [Database timeline plotter](src/mars/plotter/README.md) for SQLite with [Plotly](https://plotly.com/)
- Add and edit targets using the [Artifact Recovery Catalog (ARC) Manager](src/mars/catalog/README.md)
- Export and import anonymized exemplar catalog packages to share with other MARS users
- In-depth HTML documentation (no internet required)

### v1.0 Report Modules

- [WiFi activity](src/mars/report_modules/wifi_report_generator/README.md) and location mapping
- [Biome parsing](src/mars/report_modules/biome_parser/README.md) with CCL Group's [SEGB parser](https://github.com/cclgroupltd/ccl-segb)
- [Firefox JSONLZ4](src/mars/report_modules/firefox_jsonlz4_parser/README.md) parsing
- [Firefox cache](src/mars/report_modules/firefox_cache_parser/README.md) parsing (extract images, HTML, etc.)

Repo: [https://github.com/WarpedWing/MARS](https://github.com/WarpedWing/MARS)
<br/>
<br/>

## PhotoRec Refinery

![PhotoRec Refinery - Main](https://github.com/WarpedWing/WarpedWing/blob/main/refinery-mainwindow.png)

A desktop companion for the file recovery application [PhotoRec](https://www.cgsecurity.org/wiki/PhotoRec) that helps you auto-remove filetypes you don't want — and keep the carved files organized.

- Live‑monitors PhotoRec’s output and automatically deletes unwanted types in completed `recup_dir.X` folders
- One‑click “Process” for existing PhotoRec output that’s already finished
- Optional reorganization into type‑based folders with configurable subfolder batch sizes

| From This    | To This |
| -------- | ------- |
| ![PhotRec Refinery - Ugly Folders](https://github.com/WarpedWing/WarpedWing/blob/main/refinery-uglyfolders.png)  | ![PhotRec Refinery - Reorganized Folders](https://github.com/WarpedWing/WarpedWing/blob/main/refinery-cleanfolders.png)    |

Repo: [https://github.com/nbenford/photorec-refinery](https://github.com/WarpedWing/photorec-refinery)
<br/>
<br/>
