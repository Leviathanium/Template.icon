# NextUI Icon Component Template

This repository contains a template for creating icon components for NextUI devices.

## What are Icon Components?

Icon components replace the system, tool, and collection icons used throughout the NextUI interface. You can provide custom icons for ROM systems, tools, and user-created collections.

## Directory Structure

- `manifest.json` - Component metadata and icon path mappings
- `preview.png` - Component preview image (replace with your preview)
- `SystemIcons/` - Icons for systems and main menu items
  - `Collections.png` - Collections menu icon
  - `Recently Played.png` - Recently played list icon
  - `Tools.png` - Tools menu icon
  - `Game Boy Advance (GBA).png` - System-specific icon (include tag in parentheses)
- `ToolIcons/` - Icons for individual tools
  - `Settings.png` - Icon for the Settings tool
- `CollectionIcons/` - Icons for user collections
  - `Favorites.png` - Icon for the Favorites collection

## Getting Started

1. Replace the placeholder `preview.png` with a preview that demonstrates your icon style
2. Update the `manifest.json` with your component information (name, author, etc.)
3. Replace the placeholder icon files with your custom icons
4. Add additional icons as needed, following the naming conventions
5. Update the `content` and `path_mappings` sections in manifest.json for any new icons
6. When complete, commit your changes and update the `NextUI-Themes` catalog

## Icon Requirements

- PNG format with transparency
- Recommended size is at least 200x200 pixels (the system will resize as needed)
- All icons should follow a consistent style
- System icons must include the system tag in parentheses (e.g., Game Boy Advance (GBA).png)
- Tool icons must match the tool name exactly (e.g., Settings.png for Settings.pak)
- Collection icons must match the collection folder name exactly

## Critical System Icons

Make sure to include these important system icons:
- `Collections.png` - Icon for the collections menu
- `Recently Played.png` - Icon for the recently played list
- `Tools.png` - Icon for the tools menu

## For more information, see the full component documentation
