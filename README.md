# FCI Assiut Graduation Team Members Directory

A modern, responsive web application for displaying and managing FCI (Faculty of Computers and Information) Assiut University graduation team members' information. The application provides a clean interface to view, search, and filter team members across different departments (CS, IT, IS).

## Live Demo

Visit the live application at: [https://black301.github.io/version_3/](https://black301.github.io/version_3/)

## Features

- 📱 **Responsive Design**: Works seamlessly on both desktop and mobile devices
- 🔍 **Advanced Search**: Search across all fields in real-time
- 🏷️ **Department Filtering**: Filter members by department (CS, IT, IS)
- 📊 **Sortable Columns**: Click on column headers to sort data
- 🔄 **Real-time Updates**: Data is fetched directly from Google Sheets
- 📱 **Mobile-Optimized View**: Card-based layout for mobile devices
- 🔗 **Smart Link Detection**: Automatically detects and formats URLs
- 🎨 **Modern UI**: Clean and professional design with department-specific color coding

## Technical Details

- **Frontend**: Pure HTML, CSS, and JavaScript
- **Data Source**: Google Sheets (CSV format)
- **Dependencies**:
  - PapaParse (for CSV parsing)
  - No additional frameworks required
- **Hosting**: GitHub Pages

## Usage

1. **Viewing Data**:
   - The table view shows all team members in a sortable format
   - On mobile devices, data is displayed in expandable cards

2. **Searching**:
   - Use the search box to filter members by any field
   - Search is performed in real-time as you type

3. **Filtering**:
   - Click department buttons (All, CS, IT, IS) to filter by department
   - Multiple filters can be combined with search

4. **Sorting**:
   - Click column headers to sort by that field
   - Click again to reverse the sort order

5. **Refreshing Data**:
   - Click the "Refresh" button to fetch the latest data from Google Sheets

## Data Format

The application expects the following data structure in your Google Sheet:

- **Required Fields**:
  - Name (or Full Name)
  - Department (CS, IT, or IS)

- **Optional Fields**:
  - LinkedIn Profile URL
  - CV URL
  - Any additional information columns

## Browser Support

The application is compatible with all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the MIT License. 