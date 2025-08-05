# FreezerMap

A web-based, drag-and-drop inventory tracker for managing frozen cell vials in -80°C freezers. Designed for ease-of-use in lab environments, this tool supports live editing, color-coded projects, label printing, and exportable logs — all within a sleek single-page interface.

![Laboratory](https://img.shields.io/badge/domain-laboratory-blue.svg)
![Research](https://img.shields.io/badge/application-research-green.svg)
![Sample Management](https://img.shields.io/badge/tracking-samples-orange.svg)
---

## Project Overview

This project was created to streamline the tracking of cryopreserved samples in academic or biotech lab settings. Many existing systems are clunky, slow, or expensive. This tool aims to be:

- **Visual**: Shows the entire freezer box (10x10) with clear status indicators  
- **Interactive**: Drag to rearrange, click to edit, hover for info  
- **Portable**: All data stored client-side, no login or backend required  
- **Label-Ready**: Custom label printing for Brady printers, NiceLabel, and ZPL

---

## Features

- **100-position grid** (A1–J10) with occupancy tracking  
- **Color-coded project tags** with automatic legend updates  
- Sample metadata support:
  - Project name
  - Cell type (single cell, pool, bulk sort)
  - Clone ID
  - Freeze date
- Export to:
  - `.CSV` (Excel-compatible)
  - `.JSON` (full backup)
  - ZPL (Zebra label printers)
  - NiceLabel
  - Brady BMP51/BBP12 formats
- **Label preview** with custom settings (size, format, QR codes)
- Smart defaults like today's date and live data queueing
- Full reset and data import options
- Label queue + selection mode for bulk actions

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML/CSS   | Responsive UI and styling |
| JavaScript | Dynamic grid logic, modals, drag-and-drop |
| LocalStorage | Client-side data persistence |
| Blob API   | File export and import |
| Brady/NiceLabel/ZPL | Printer compatibility formats |

---

## Getting Started

To use the tool:

1. Download or clone the repository  
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge)
3. Begin adding samples!

---

## Use Cases

- Inventory management for cell lines, clones, or pooled populations
- Preparing labels for cryovials with integrated position, date, QR, etc.
- Exporting metadata for electronic lab notebooks (ELNs) or LIMS
- Teaching students proper sample documentation habits

---

## Planned Enhancements

- Multi-box/multi-freezer tracking support  
- Dark mode toggle  
- Barcode scanning for retrieval  
- Optional backend for shared lab access  

---

## Author

Developed by Sophia DeGeorgia, PhD as a personal side project while working in a research lab. Inspired by real-world frustrations with commercial freezer inventory tools.

---



## Feedback

Open an issue or [contact me](mailto:sdegeorgia@gmail.com) — I'd love to hear how you're using this!



