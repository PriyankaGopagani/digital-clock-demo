# Digital Clock (with Dark/Light Mode and Date)

## Overview
A simple, responsive digital clock web app that displays the current time and the full date. It includes a dark/light mode toggle with smooth transitions and remembers your preference across visits. No external dependencies.

## Setup
- Download the repository or this single file.
- Open index.html in any modern web browser.

That's it—no build steps required.

## Usage
- Time updates every second automatically.
- The current date is shown beneath the time in your locale format (e.g., Wednesday, October 15, 2025).
- Click the Dark/Light toggle in the top-right to switch themes.
  - The app will remember your choice (stored in localStorage).
  - If you haven’t chosen a theme yet, it follows your system’s preferred color scheme.

## Improvements in Round 2
This version enhances the previous digital clock by:
- Adding a dark/light mode toggle with:
  - Smooth theme transitions
  - Preference persistence via localStorage
  - Automatic system theme detection and live updates when your OS theme changes (unless overridden)
- Displaying the current date below the time using your locale for formatting
- UI polish and accessibility:
  - Clear, high-contrast styles for both themes
  - Accessible toggle with ARIA attributes
  - Responsive typography with tabular numerals for stable time layout