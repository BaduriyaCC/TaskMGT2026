# Task Management System 2026
**Baduriya Central College - Mawanella**

An offline, browser-based Task Management System for staff.

## Features
- **Staff Management**: Add, Edit, Delete staff profiles. Bulk upload via Excel.
- **Task Management**: Assign tasks, track status (Pending/Completed), deadlines.
- **Reports**: Generate PDF reports for individual or all staff. Visual charts.
- **Data Safety**: All data is stored locally in your browser (LocalStorage).
- **Import/Export**: Backup your data to JSON and restore it on another device.
- **Offline Ready**: Works without an internet connection.

## Setup Instructions
1. This system comes with all necessary libraries pre-downloaded in `assets/js/lib/`.
2. Simply open `index.html` in any modern web browser description (Chrome, Edge, Firefox).
3. No installation or internet connection is required to run the app.

## Project Structure
- `index.html` - Main application file.
- `assets/css/` - Styling (Premium UI).
- `assets/js/script.js` - Application logic.
- `assets/js/lib/` - Offline libraries (Chart.js, jsPDF, etc.).

## Troubleshooting
- **Charts/PDFs not working?** Ensure the files in `assets/js/lib/` are present. If they are missing, you may need to download them or connect to the internet to let the system fetch them (if fallback is configured, though this version builds for strict offline use).
- **Data lost?** Data is stored in the browser. If you clear cache, data may be lost. Use the "Settings & Data" tab to "Export Data" regularly for backup.

## Credits
Built for Baduriya Central College.
2026
