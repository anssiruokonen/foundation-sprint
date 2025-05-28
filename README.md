# Foundation Sprint Workshop Tool

A secure, single-page workshop facilitation tool for conducting Foundation Sprint workshops. This tool works entirely client-side and is hosted on GitHub Pages.

## Features

- Password protection for secure access
- Auto-save functionality using localStorage
- Module-based workshop structure with timers
- Dark/light theme support
- Export capabilities (JSON, PDF, Markdown, CSV)
- Responsive design for all devices

## Getting Started

1. Access the workshop tool at https://anssiruokonen.github.io/foundation-sprint/
2. Enter the password to access the workshop
3. Optionally check "Remember me for 24 hours" to skip password entry on future visits

## Workshop Modules

The workshop consists of four modules:

1. **Basics** (90 minutes)
   - Company/Project Name
   - Problem Statement

2. **Differentiation** (90 minutes)
   - Main Competitors
   - Key Differentiators

3. **Approach** (90 minutes)
   - Approach Description
   - Potential Risks

4. **MVP & Hypothesis** (60 minutes)
   - MVP Description
   - Founding Hypothesis

## Using the Workshop Tool

### Navigation
- Use the "Previous" and "Next" buttons to move between modules
- Each module has a timer showing remaining time
- A warning will appear when 5 minutes remain

### Data Persistence
- All data is automatically saved every 30 seconds
- Data is stored locally in your browser
- Previous workshop data can be loaded automatically

### Exporting Results
Click the export buttons to save your workshop results in different formats:
- PDF: Formatted document with all workshop results
- JSON: Raw data for technical teams
- Markdown: Easy-to-share documentation
- CSV: Spreadsheet-friendly format

### Theme
- Toggle between light and dark themes using the button in the top-right corner
- Theme preference is saved between sessions

## Security

- All data is stored locally in your browser
- No data is sent to external servers
- Password protection prevents unauthorized access
- Session timeout after 24 hours (if "Remember me" is checked)

## Browser Support

The workshop tool is compatible with:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Development

To modify or enhance the workshop tool:

1. Clone the repository
2. Make your changes to `index.html`
3. Test locally
4. Commit and push to GitHub
5. GitHub Pages will automatically deploy your changes

## License

This project is licensed under the MIT License - see the LICENSE file for details. 