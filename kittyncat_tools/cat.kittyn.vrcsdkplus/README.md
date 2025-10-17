# cátte — VRCSDK+

Enhanced custom inspectors for VRChat SDK Expression Menus and Parameters with improved functionality and quality of life features.

## Features

### Custom VRCExpression Parameters Inspector
- Dropdown of parameters available in playable controllers for easy selection
- Add parameters to playable controllers directly from the editor
- Warnings and cleanup tools to ensure all parameters are valid
- Ability to merge two expression parameters
- Re-orderable list with easy deletion
- Dynamic, clean, and compact UI

### Custom VRCExpression Menu Inspector
- Menu history to switch between previously visited menus
- QoL buttons: Copy, Paste, Duplicate, and Move
- Add parameters to expression parameters directly from the editor
- Quickly add new SubMenu assets to SubMenu controls
- Set styling for controls: Bold, Italic, and Color
- Toggle Compact Mode through the window's options
- Warnings to ensure all parameters are valid
- Dynamic, clean, and compact UI

### Avatar Descriptor Quick Setup
Adds "Quick Setup" context menu button to VRC Avatar Descriptor:
- Sets View Position based on Eye bones
- Triggers "Auto-Detect" for lipsync
- Sets Eye bones and rotation states
- Automatically sets Eyelids type, Mesh, and Blinks if found

## Installation

Install via VRChat Creator Companion (VCC) or add to your Unity project's Packages folder.

**Requirements**: VRChat SDK3 Avatars 3.0.0 or later

## Usage

VRCSDK+ provides alternative custom inspectors to the native VRCSDK expression menu and parameters. The enhanced inspectors appear automatically when you select Expression Menu or Expression Parameters assets.

You can revert to original editors using the context menu of the respective object.

## Important Notes

- VRCSDK+ does **not** modify the VRCSDK in any way
- VRCSDK+ does **not** require a VRC+ subscription
- All features are non-destructive and can be reverted

## License

MIT License - see LICENSE.md file for details
