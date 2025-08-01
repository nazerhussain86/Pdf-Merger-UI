# Pdf-Merger-UI
Project Name: PDF Merger UI (Bootstrap 5 + JavaScript)
Overview
This project is a web-based user interface designed for merging multiple PDF files entirely in the browser. It provides a clean, modern, and responsive experience built with Bootstrap 5 for layout and styling, and integrates powerful JavaScript libraries — PDF.js for PDF previewing and pdf-lib for merging PDF documents on the client side.

Key Features
Drag-and-Drop Upload Area:
Users can drag and drop multiple PDF files into a dedicated upload zone or click to browse and select files.

File Management List:
Uploaded PDF files are displayed in a clear, interactive list where each file can be selected for preview, reordered via “move up” and “move down” buttons, or removed with a close (“×”) button.

PDF Preview:
When a file is selected from the list, the first page of that PDF is rendered instantly using PDF.js on an HTML canvas, giving users a quick glance without leaving the UI.

Reorder Files:
Users can precisely control the merging order by moving files up or down in the list, maintaining full control before merging.

Merge and Download:
A “Merge PDFs” button merges all uploaded PDFs in the selected order into a single file using the pdf-lib JavaScript library.
The merged PDF is then immediately downloadable in the browser without any need for backend processing.

Add More PDFs:
An “Add PDF” button lets users append more files after the initial upload seamlessly.

Technologies Used
Bootstrap 5: For responsive layout, styling, and UI components.

PDF.js: Renders previews of PDF files client-side in the browser.

pdf-lib: Performs client-side PDF merging (combining pages from multiple PDFs).

Vanilla JavaScript: Handles user interactions (drag-drop, file management, preview rendering, and merging).

User Experience Flow
The user drags PDFs into the upload area or clicks to select files.

Uploaded files appear in a list with options to remove or reorder.

Clicking a file in the list shows its first page preview.

The “Merge PDFs” button activates once two or more files are uploaded.

Clicking “Merge PDFs” merges the files locally and prompts the user to download the combined PDF.

The user can repeat the process with new files or reorder existing ones before merging again.

Advantages
No server needed: All processing is client-side, preserving privacy and improving speed.

Intuitive Interface: Drag-and-drop, preview, and reorder make PDF merging straightforward.

Extensible: The UI can be enhanced with more features or connected to backend APIs if desired.
