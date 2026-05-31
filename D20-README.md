# D20 Thermal Sticker Generator

Browser-based tool for generating printable stickers optimized for the D20 Mini Sticker Printer and other 57mm thermal printers.

## About the D20 Mini Sticker Printer

The D20 Mini Sticker Printer is a pocket-sized, Bluetooth-enabled device that uses inkless thermal technology to print black-and-white stickers, labels, and memos directly from your phone.

**Specifications:**
- **Technology**: Inkless thermal printing (monochrome only)
- **Connectivity**: Bluetooth via mobile apps (Nada Print, Jaden's printer app, etc.)
- **Paper Size**: 57mm wide continuous thermal and sticker rolls
- **Design**: Lightweight (approx. 163g), roughly 3.5" × 3.5" × 1.5"
- **Battery**: Rechargeable via USB-C (1200-1300mAh)

## Features

### Sticker Templates

The generator includes several pre-made sticker types:

1. **Daily Habit Tracker** - Checkbox list for daily habits
2. **To-Do List** - Lined items with checkboxes
3. **Date Stamp** - Large date display with dot grid notes area
4. **Weekly Habit Grid** - 7-day habit tracker with multiple habits
5. **Numbered Checklist** - Numbered items with lines
6. **Blank Label** - Customizable title with dot grid

### Customization Options

- **Adjustable Height**: Set custom sticker height (20-200mm) while width stays at 57mm
- **Checkbox Styles**: Square, circle, or rounded corners
- **Font Sizes**: Small (9pt), medium (10pt), or large (12pt)
- **Custom Content**: Add your own habits, tasks, and titles
- **Batch Export**: Generate multiple copies of the same sticker

### Optimizations for Thermal Printing

- **Pure black and white** - No colors or grayscale (thermal printers only print black)
- **High contrast** - Bold lines and clear text for crisp thermal output
- **Fixed 57mm width** - Matches standard thermal paper roll size
- **Clean borders** - Simple designs that print reliably on thermal paper
- **No complex graphics** - Avoids patterns that may not render well on thermal printers

## Usage

### Basic Workflow

1. **Open the Generator**
   - Open `d20-sticker-generator.html` in any modern web browser
   - No installation or internet connection required

2. **Choose Sticker Type**
   - Select from the dropdown menu in the sidebar
   - Options: Habit tracker, to-do list, date stamp, etc.

3. **Customize Content**
   - Add or remove habits/items using the + Add button
   - Edit text directly in the preview
   - Adjust height, checkbox style, and font size

4. **Adjust Dimensions**
   - Width is fixed at 57mm for thermal paper compatibility
   - Set custom height based on your needs (default: 40mm)

5. **Export**
   - Click **"Download PNG"** for single sticker image
   - Click **"Print / PDF"** to save as PDF
   - Use **"Export Batch"** to create multiple copies

### Printing to Your D20 Printer

#### Method 1: Via Mobile App (Recommended)

1. Export your sticker design as PNG or PDF
2. Transfer the file to your phone (email, cloud storage, AirDrop, etc.)
3. Open the file in your D20 printer app (Nada Print, Jaden's app, etc.)
4. Connect to your D20 printer via Bluetooth
5. Print directly from the app

#### Method 2: Screenshot Method

1. Generate your sticker in the browser
2. Take a screenshot of the preview
3. Crop to just the sticker area (remove borders)
4. Transfer to phone and print via printer app

#### Method 3: Direct Browser Print

1. Click the **"Print"** button in the generator
2. Select "Save as PDF" as your printer
3. Open PDF on phone and print via D20 app

## Tips for Best Results

### Design Tips

- **Keep it simple**: Thermal printers work best with clean, bold designs
- **Test first**: Print a test sticker to check sizing before batch printing
- **Avoid fine details**: Very small text or thin lines may not print clearly
- **Use high contrast**: Solid black on white background works best
- **Mind the margins**: Leave some space around edges for clean cuts

### Paper Tips

- Use genuine thermal sticker paper for best adhesion
- Standard thermal paper works but won't have adhesive backing
- 57mm is the standard width - don't try to print on narrower paper
- Roll paper allows continuous printing of multiple stickers

### Printer Settings

- Ensure Bluetooth is enabled on both phone and printer
- Keep printer charged (prints may fade with low battery)
- Clean the print head periodically for consistent quality
- Store unused thermal paper away from heat and light

## Common Use Cases

- **Planner Stickers**: Daily habits, weekly trackers, date stamps
- **Organization**: Storage labels, jar labels, file folder labels
- **Bullet Journal**: Custom icons, headers, decorative elements
- **Study Aids**: To-do lists, subject headers, reminder notes
- **Crafts**: Gift tags, package labels, project labels
- **Kitchen**: Pantry labels, meal prep dates, recipe tags

## Customization Examples

### Daily Habit Tracker
- Add your daily habits: "Drink water", "Exercise", "Read"
- Choose circle checkboxes for a clean look
- Set height to 50mm for comfortable spacing

### Weekly Meal Prep Labels
- Use "Blank Label" template
- Title: Day of the week (Monday, Tuesday, etc.)
- Height: 30mm for compact labels
- Print 7 copies for the whole week

### Project To-Do Lists
- Use "Numbered Checklist" template
- Custom title with project name
- Height: 60mm for longer lists
- Export batch of 5 for multiple projects

### Date Stamps for Journal
- Use "Date Stamp" template
- Set to current date
- Height: 40mm
- Print batch of 31 for the whole month

## Technical Details

### Dimensions
- **Width**: Fixed at 57mm (215px at 96 DPI)
- **Height**: Customizable 20-200mm (75-755px at 96 DPI)
- **Resolution**: Optimized for typical thermal printer resolution (203 DPI)

### File Format
- **Output**: PNG, PDF, or direct print
- **Color Mode**: 1-bit black and white
- **DPI**: 96 for screen, scales to 203 for thermal printing

### Browser Compatibility
- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile browsers: Supported but desktop recommended for editing

## Troubleshooting

### Sticker prints too small/large
- Check printer app settings for "Fit to page" or "Scale"
- Set printer to 100% scale / actual size
- Verify the image dimensions match expected mm size

### Lines are too thin/thick
- Adjust using browser zoom before exporting
- Modify CSS border widths if needed
- Test print to find optimal thickness

### Text is blurry
- Use the "Print" button instead of screenshots
- Export as PDF for highest quality
- Ensure printer head is clean

### Stickers don't stick
- Use actual thermal sticker paper, not regular thermal paper
- Check paper backing - some require peeling
- Ensure paper is loaded correctly in printer

## License

This project is licensed under the GNU General Public License v3.0, same as the original TN Insert Generator.

## Credits

Based on the Traveler's Notebook Insert Generator, adapted for thermal sticker printing on the D20 Mini Sticker Printer and similar 57mm thermal devices.
