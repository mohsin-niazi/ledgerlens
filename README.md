# LedgerLens

A local-first preflight for finance CSV exports.

[Open the live demo](https://mohsin-niazi.github.io/ledgerlens/) · [Source code](https://github.com/mohsin-niazi/ledgerlens)

## Checks

- Duplicate reference values
- Missing dates, references, or amounts
- Unrecognized dates and non-numeric amounts
- Downloadable findings report with source row numbers

## Use it

Choose a CSV (up to 15 MB) or load the sample. LedgerLens detects date, reference, and amount columns from their headers. Review the results, then download the report.

## Privacy and scope

The app reads the selected file in your browser tab. It has no backend and does not upload your data. Checks cover common file issues; they do not replace your normal accounting review.

Built as a small, dependency-free static app.
