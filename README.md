# AI-Based Resume Skill Analyzer

A single-page website with a working resume analyzer demo.

## How to run
Open `index.html` in any modern browser (Chrome, Edge, Firefox). No installation or server is needed.
An internet connection is required the first time because the PDF/DOCX/PDF-report libraries load from cdnjs.cloudflare.com.

## Features
- Upload a resume (PDF or DOCX) and choose one of 30 job roles
- Skill match score, matched / missing skills
- AI recommendations, career suggestions, experience and education analysis
- Overall resume score and dashboard charts
- Download a PDF analysis report
- Invalid-document detection (assignments, marksheets, invoices, certificates, empty/corrupted/locked/image-only PDFs)

## Notes
- Analysis is keyword-based and runs entirely in the browser.
- JPG/PNG resume upload needs Claude to read the image, so it only works on the hosted claude.ai version, not in this offline copy.
- Libraries used: pdf.js, mammoth.js, jsPDF (loaded from cdnjs).
