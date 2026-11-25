# Shree Sai Solar – Document Generators

Static pages for GitHub Pages. No build step.

- `quotation-generator/` – Quotation (Download PDF / Print)
- `invoice-generator/` – Tax Invoice & Receipt (Download PDF / Print)
- `lib/html2pdf.bundle.min.js` – html2pdf.js 0.10.1 (MIT licence), used by both pages for Download PDF.
  The pages load this copy first and fall back to the cdnjs / jsDelivr CDNs only if it is missing.

Print uses the browser's own print dialog and needs no library.
