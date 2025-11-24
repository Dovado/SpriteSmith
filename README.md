# SpriteSmith
SpriteSmith lets you slice sprite sheets, preview animations, scale images, and export game-ready frames with ease. Ideal for pixel artists and developers needing fast grid detection, precise slicing, and quick animation previews.

# SpriteSmith

A powerful desktop sprite sheet utility built with Flutter that lets you visually test cut regions on character sheets, preview animations, create named sequences, and export exact coordinates for use in your own games.

## Short Description

A desktop sprite sheet utility built with Flutter that lets you visually test cut regions on character sheets, preview animations, and export exact coordinates for use in your own games.

## Features

### Core Functionality
- **Load Any Size Sprite Sheet** - Support for PNG, JPG, and JPEG formats
- **Auto-Detect Grid Layout** - Automatically detects frame dimensions and grid structure
- **Visual Grid Overlay** - See calculated frames overlaid on your sprite sheet in real-time
- **Manual Fine-Tuning** - Adjust frame width, height, offsets, and spacing with precise controls
- **Full-Screen Viewer** - Click the sprite sheet to view it full-screen with zoom and pan controls
- **Frame Validation** - Visual warnings for overlapping or out-of-bounds frames

### Frame Selection & Sequences
- **Multi-Frame Selection** - Select multiple frames using checkboxes
- **Named Animation Sequences** - Create and name animation sequences (e.g., `walking_south`, `attack`)
- **Sequence Management** - Save, load, and delete custom animation sequences
- **Frame Thumbnails** - Visual thumbnails for easy frame identification
- **Quick Selection Tools** - Select all frames or clear selection with one click

### Animation Preview
- **Real-Time Preview** - Preview your animations with adjustable FPS (1-30 FPS)
- **Sequence Playback** - Preview individual sequences or all frames
- **Advanced Animation Timing** - Set per-frame duration for custom timing
- **Easing Curves** - Choose from 7 easing types: linear, easeIn, easeOut, easeInOut, bounce, elastic, back
- **Timeline Visualization** - Visual timeline showing frame durations and easing types
- **Quick Actions** - Reset all timings, equalize durations, or set all to linear

### Export Options
- **Code Export** - Export Flutter/Dart code with frame rectangles and sequences
  - Includes helper methods (`getFrame()`, `getSequence()`)
  - Ready-to-use `SpriteSheet` class
  - JSON format for all frames and sequences
- **Animated GIF** - Export animations as GIF files (looped or single play)
- **PNG Sequence** - Export individual frame files (game-dev format)
- **Spritesheet Export** - Export single PNG with metadata JSON
- **Individual Frame Export** - Save any frame as a separate PNG file
- **Copy to Clipboard** - Copy export code directly to clipboard

### Image Processing
- **Image Scaling** - Scale images from 50% to 200% or set specific dimensions
- **Batch Image Converter** - Convert multiple images at once
  - Scale by percentage or specific dimensions
  - Export as ZIP file with all converted images
- **Resize & Save** - Save resized versions of your sprite sheets

### Workflow Tools
- **Preset Management** - Save and load parameter presets for quick reuse
- **Undo/Redo** - Experiment safely with full undo/redo support
- **Auto-Save & Recovery** - Automatic saving every 30 seconds with recovery on restart
- **Recent Files** - Quick access to recently opened sprite sheets
- **Settings Persistence** - All preferences saved across sessions

### Customization
- **Theme Support** - Light, Dark, or System theme
- **Color Customization** - Choose your preferred accent color
- **Export Language** - Select code export format (Dart, C#, C++, JavaScript, Python, Lua, Rust)
- **Configurable Options** - Toggle auto-detect grid, auto-save, and more

## Download & Installation

### Windows

1. Download the latest release from [GitHub Releases](#) or [itch.io](#)
2. Extract the ZIP file to a folder of your choice
3. Run `SpriteSmith.exe`
4. No installation required - it's a portable application

### macOS & Linux

Coming soon! Check back for updates.

## How to Use

### Getting Started

1. **Launch the app** and click "Pick File" to load your sprite sheet
2. **Auto-detect grid** - Click "Auto-Detect" to automatically detect frame layout, or adjust manually
3. **Fine-tune parameters** - Adjust frame width, height, offsets, and spacing until frames align perfectly
4. **Preview frames** - View calculated frames in the visual grid overlay
5. **Use Undo/Redo** - Experiment safely with full undo/redo support

### Creating Animation Sequences

1. Navigate to **"Frame Sequences & Export"** from the main screen
2. **Select frames** - Click checkboxes on frame thumbnails to select them
3. **Create sequence** - Select 2+ frames and click "Create Sequence"
4. **Name your sequence** - Use descriptive names (e.g., `walking_south`, `attack_swing`)
5. **Preview animation** - Select a sequence to preview it in the animation viewer
6. **Adjust FPS** - Use the slider to control animation playback speed

### Advanced Animation Timing

1. Click **"Advanced"** button in the Animation Preview section
2. **Set per-frame duration** - Customize timing for each frame individually
3. **Choose easing curves** - Select from linear, easeIn, easeOut, easeInOut, bounce, elastic, or back
4. **View timeline** - See visual representation of frame durations
5. **Use quick actions** - Reset all, equalize durations, or set all to linear

### Exporting Your Work

1. **Save as Code** - Export Flutter/Dart code with frame rectangles and sequences
2. **Save as GIF** - Export animation as animated GIF (looped or single play)
3. **PNG Sequence** - Export individual frame files (game-dev format)
4. **Spritesheet** - Export single PNG with metadata JSON
5. **Save Frame as Picture** - Save individual frames as PNG files
6. **Copy to Clipboard** - Copy export code directly to clipboard

### Batch Processing

1. Access **"Batch Image Converter"** from the main screen
2. **Select multiple images** to convert at once
3. **Choose scaling method** - Scale by percentage or specific dimensions
4. **Export as ZIP** - All converted images packaged in a ZIP file

## Tips & Best Practices

- **Use presets** - Save presets for sprite sheets you work with frequently
- **Frame validation** - Pay attention to warnings about overlapping or out-of-bounds frames
- **Naming conventions** - Use snake_case for sequence names (e.g., `walking_south`, `attack_swing`)
- **Full-screen view** - Click the sprite sheet preview to view it full-screen for precise alignment
- **Experiment freely** - Use Undo/Redo liberally to try different settings
- **Auto-save** - Enable auto-save to never lose your work (saves every 30 seconds)

## Support the Developer

SpriteSmith is developed by a small independent developer. If this tool saves you time and helps with your game development, please consider supporting continued development and improvements.

**Every contribution helps!**

- **PayPal**: [Donate via PayPal](https://www.paypal.com/ncp/payment/VYET7YMM77PQ8)
- **QR Code**: Scan the QR code in the About dialog to donate

## Contact

- **Email**: clarkkentsoops@gmail.com
- **Developer**: Dovado S. Evans

## License

© 2025 Dovado S. Evans

BrightShadow Works - All rights reserved.

This software is proprietary and closed source. All rights reserved. Unauthorized copying, modification, distribution, or use of this software, via any medium, is strictly prohibited.

## Technical Details

- **Built with**: Flutter
- **Platform**: Desktop (Windows, macOS, Linux)
- **Supported Formats**: PNG, JPG, JPEG
- **Export Formats**: Dart/Flutter code, GIF, PNG sequence, Spritesheet JSON

## Changelog

### Version 1.0.0
- Initial release
- Core sprite sheet splitting functionality
- Frame selection and sequence creation
- Animation preview with FPS control
- Advanced animation timing with easing curves
- Multiple export formats (code, GIF, PNG sequence, spritesheet)
- Batch image converter
- Preset management
- Auto-save and recovery
- Theme customization
- Full-screen viewer with zoom

