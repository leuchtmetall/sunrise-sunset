> [!NOTE]
> AI usage disclosure: Most of the code in this project is AI generated.

# A simple sunrise/sunset calendar in a single html file.
This project is a calendar for displaying the sunrise and sunset times for multiple locations. It is deliberately contained in a single html file, so it can be used anywhere where html files with JavaScript are supported.

## What it shows:
- Main calendar:
  - Sunrise and sunset times for each configured location.
  - Solstice and Equinox times per location.
  - Moon phases (new, half, and full moon) with time per location.
- Detailed sun position dialog (single day):
  - sunrise, noon, sunset and day length per location.
  - 24h sun position graph for all locations, with astronomical, nautical, and civil dawn/dusk.
  - optional aligning by solar noon, to compare day length between locations.

## Configuration:
The displayed locations can be configured by editing the `locations` variable at the end of the file.
