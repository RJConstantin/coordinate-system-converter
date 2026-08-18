Coordinate System Converter

Updated user-friendly version

What changed:
- Automatically detects the coordinate columns, including reversed Northing/Easting order.
- Automatically recognizes clear latitude/longitude input.
- Tests common Alberta projected coordinate systems.
- When several systems are possible, asks the user to choose the approximate project location instead of guessing.
- Keeps GIS terminology and manual X/Y/source controls under Advanced options.
- Preserves extra table columns and downloads the converted result as CSV.

To update the existing GitHub Pages site:
1. Replace the existing index.html in the repository root with the index.html in this ZIP.
2. Commit the change to main.
3. GitHub Pages will redeploy automatically.
