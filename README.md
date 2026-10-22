# Consolidata

**An intelligent document processing and data consolidation platform for unstructured corporate data**

Bilkent University, Department of Computer Engineering, CS491/492 Senior Design Project

Consolidata reads documents that arrive from different departments or subsidiaries in different formats (Excel, CSV, PDF, Word, scanned documents, system exports) without requiring a fixed template. It maps them to a common data model, validates them, and serves them as a single structured data source. Every extracted value is stored together with its source document, so each figure in a report can be traced back to the file, page and cell it came from.

## Team

| Name | Email |
|---|---|
| Ahmet Kenan Ataman | kenan.ataman@ug.bilkent.edu.tr |
| Ece Şeşen | ece.sesen@ug.bilkent.edu.tr |
| Mehmet Emre Şahin | emresahin@ug.bilkent.edu.tr |
| Nevzat Han Altın | han.altin@ug.bilkent.edu.tr |
| Umut Çağın Özcan | cagin.ozcan@ug.bilkent.edu.tr |


## Website

The project website is served with GitHub Pages: `https://<username>.github.io/<repo-name>/`

### Repository structure

```
├── index.html        # Project website (single file)
├── .nojekyll         # Disables Jekyll processing on GitHub Pages
├── docs/
│   └── proje-taslagi.pdf
└── README.md
```

### Adding a new report

1. Put the PDF in the `docs/` folder (avoid spaces and non-ASCII characters in the file name).
2. In `index.html`, under "Project documents", replace `Coming soon` on the matching row with `<a href="docs/file-name.pdf">Open PDF</a>`.
