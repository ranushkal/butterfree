# Butterfree

A lightweight, client-side web application for extracting and analyzing metadata from PDF files.

## Overview

Butterfree is a browser-based tool that allows users to upload PDF files and extract comprehensive metadata without requiring a backend server. All processing happens directly in your browser, ensuring privacy and speed.

## Features

### PDF Metadata Extraction
Extract detailed information from your PDF files:
- **Basic Information**: File name, size, type, last modified date
- **Document Properties**: Title, author, subject, creator, producer
- **Technical Details**: Creation date, modification date, page count, PDF version

### Interactive Data Management
- **Drag & Drop Upload**: Simply drag PDF files into the upload area
- **Customizable View**: Toggle which metadata fields to display
- **Sortable Columns**: Click any column header to sort data
- **Smart Filtering**: Filter files by any metadata field and highlight non-matching entries
- **Real-time Statistics**: View total files, matching criteria, and filtered results

### Export Options
- **CSV Export**: Download metadata as comma-separated values
- **JSON Export**: Export data in JSON format for further processing
- Both formats respect your selected metadata fields

## Usage

1. **Open the Application**: Open `butterfree` file in any modern web browser
2. **Upload Files**: Click "Choose Files" or drag and drop PDF files into the upload area
3. **Customize View**: Use the "Metadata Fields" panel to select which fields to display
4. **Filter Data**: Use the "Search & Filter" panel to find specific files
5. **Export Results**: Click "Export to CSV" or "Export to JSON" to download your data

## Technical Details

- **Pure Client-Side**: No server required, all processing happens in-browser
- **Framework**: Vanilla JavaScript with PDF.js library (v3.11.174)
- **Privacy-Focused**: Your files never leave your computer
- **No Installation**: Just open the HTML file in a browser
- **Responsive Design**: Works on desktop and mobile devices

## Browser Compatibility

Requires a modern browser with support for:
- ES6+ JavaScript
- File API
- Blob API
- Modern CSS (Grid, Flexbox)

Recommended browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+

## File Support

Currently supports:
- PDF files (.pdf)

## Limitations

- Large PDF files (>100MB) may cause performance issues due to browser memory constraints
- Data is only stored in memory during the session (no persistence)
- Only PDF format supported currently

## Getting Started

Simply open the `butterfree` file in your web browser. No installation or setup required!

## Use Cases

- Document management and auditing
- Batch PDF metadata analysis
- Research and cataloging
- Quality assurance for PDF documents
- Digital asset organization

## License

This project is provided as-is for educational and personal use.
