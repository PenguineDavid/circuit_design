# Circuit Diagram Designer – Documentation

## Overview

Circuit Diagram Designer is a web-based application for creating professional electronic circuit diagrams using classic schematic symbols. It provides an intuitive drag-and-drop interface with grid snapping, real-time editing, and export capabilities.

---

## Features

### Core Functionality

- **Drag & Drop Components**: 12+ electronic components with accurate schematic symbols  
- **Grid Snapping**: All elements snap to a 20px grid for perfect alignment  
- **Wire Drawing**: Connect components with automatic grid snapping  
- **Text Labels**: Add annotations and component values  
- **Real-time Editing**: Modify properties instantly  
- **Export as PNG**: Generate high-resolution circuit diagrams  
- **Undo / Redo**:  
  - Undo: `Ctrl + Z`  
  - Redo: `Ctrl + Y` / `Ctrl + Shift + Z`  
- **Zoom & Pan**: Full canvas navigation controls  

---

## Component Library

### Basic Components

- **Resistor**: IEC rectangular symbol  
- **NPN Transistor**: Classic symbol with B / C / E labels  
- **PNP Transistor**: Classic symbol with B / C / E labels  
- **Capacitor**: Parallel plate symbol  
- **Diode**: Triangle with cathode bar  
- **Switch**: Hinged contact symbol  

### Power & Ground

- **Power Source**: Circle with `+` symbol  
- **Ground**: Chassis ground symbol  
- **Battery**: 6-plate stack with `+ / -` labels  

### Input & Output

- **LED**: Diode with emission arrows  
- **Motor**: Circle with `M`  
- **Speaker**: IEC speaker symbol  

---

## User Interface

### Header Section

Contains application controls:

- **Logo & Title**: *Circuit Diagram Designer* with microchip icon  
- **Help Button**: Opens comprehensive help modal  
- **Keybinds Button**: Shows keyboard shortcuts reference  
- **Wire Mode Button**: Toggle wire drawing mode (`W`)  
- **Text Mode Button**: Toggle text placement mode (`T`)  
- **Clear All Button**: Reset entire canvas  
- **Export Button**: Generate and download PNG (`E`)  

---

### Left Sidebar

Organized into three collapsible sections:

- **Basic Components**: Resistor, transistors, capacitor, diode, switch  
- **Power & Ground**: Power source, ground, battery  
- **Input & Output**: LED, motor, speaker  

Each component is represented as a draggable card with icon and label.

---

### Canvas Area

- **Grid Background**: 20px grid with major lines every 5 cells  
- **Zoom Controls**: `+` / `-` buttons and reset zoom  
- **Mode Indicator**: Shows active mode (wire / text)  
- **Grid Info**: Shows current grid size and key shortcuts  
- **Selection Hint**: Quick start instructions  

---

### Properties Panel (Right)

Appears when items are selected with context-sensitive options.

#### For Components

- Component label (e.g. `R1`, `Q2`)  
- Value (e.g. `10kΩ`, `5V`)  
- Color picker  
- Rotate 90° (`R`)  
- Flip horizontal (`F`)  
- Delete (`Del`)  

#### For Wires

- Wire color picker  

#### For Text

- Text content  
- Font size slider (10–36px)  
- Color picker  

---

## How to Use

### Getting Started

1. Open the application in a modern web browser  
2. Drag components from the sidebar to the canvas  
3. Connect components using **Wire Mode** (`W`)  
4. Add labels using **Text Mode** (`T`)  
5. Customize properties by clicking on any element  
6. Export your diagram (`E`)  

---

### Detailed Workflow

#### Adding Components

1. Hover over any component in the sidebar  
2. Click and drag to the canvas  
3. Release to drop (snaps to grid)  
4. Components receive default labels (`R1`, `C1`, `Q1`, etc.)  

#### Connecting Components

1. Activate **Wire Mode** (`W`)  
2. Click starting grid point  
3. Click ending grid point  
4. Wire connects automatically  
5. Press `ESC` or toggle Wire Mode to exit  

#### Editing Elements

- **Select**: Click any component, wire, or text  
- **Move**: Drag selected item (snaps to grid)  
- **Rotate**: `R`  
- **Flip**: `F`  
- **Delete**: `Delete`  
- **Edit Properties**: Use the properties panel  

---

### Canvas Navigation

- **Pan**: Drag empty canvas or hold `Space` + drag  
- **Zoom**: Mouse wheel (`Ctrl` for fine control)  
- **Reset View**: Reset zoom button  

---

## Keyboard Shortcuts

| Key Combination | Action | Description |
|----------------|-------|-------------|
| W | Wire Mode | Toggle wire drawing |
| T | Text Mode | Toggle text placement |
| E | Export | Download PNG |
| R | Rotate | Rotate selected component |
| F | Flip | Flip selected component |
| Delete | Delete | Remove selected item |
| ESC | Deselect | Clear selection |
| Ctrl + Z | Undo | Reverse last action |
| Ctrl + Y / Ctrl + Shift + Z | Redo | Restore action |
| Ctrl + Mouse Wheel | Zoom | Zoom canvas |
| Space + Drag | Pan | Move canvas |
| G | Toggle Grid | Show / hide grid |

---

## Mouse Controls

- **Left Click**: Select / place wire  
- **Left Click + Drag**: Move items / pan  
- **Right Click**: Context menu (future use)  
- **Middle Click + Drag**: Pan canvas  
- **Drag from Sidebar**: Add component  

---

## Grid System

- **Grid Size**: 20px at 100% zoom  
- **Snapping**: Enabled for all elements  
- **Major Lines**: Every 5 cells (100px)  
- **Visual Feedback**: Snap indicators during placement  

---

## Export Features

### Image Export

1. Click **Export** (`E`)  
2. Preview modal opens  
3. Right-click image → *Save image as…*  

### Export Quality

- 2× resolution scale  
- White background  
- Preserves colors and labels  

---

## Technical Details

### Browser Compatibility

- Chrome 60+  
- Firefox 55+  
- Safari 11+  
- Edge 79+  
- Opera 50+  

### Dependencies

- Font Awesome 6.4.0  
- HTML5 Canvas  
- Modern CSS (Flexbox, Grid, Variables)  
- Vanilla JavaScript (no frameworks)  

### Storage

- Uses browser local storage  
- No server-side data storage  

---

## Tips for Professional Diagrams

- Use grid alignment  
- Label all components  
- Add component values  
- Keep wire paths clean  
- Use consistent colors  
- Export as PNG for documents  

---

## Troubleshooting

### Common Issues

#### Components Not Dragging

- Drag from the card itself  
- Check browser console (`F12`)  

#### Wire Mode Not Working

- Ensure Wire Mode is active  
- Click two different grid points  

#### Export Not Working

- Ensure canvas is not empty  
- Try saving preview image manually  

#### Performance Issues

- Limit diagrams over 100 components  
- Close unused tabs  
- Clear browser cache  

---

## Known Limitations

- Max zoom: 500%  
- Min zoom: 10%  
- No direct print support  
- No component import/export (planned)  

---

## Support

- Use Help modal  
- Review Keybinds modal  
- Update browser  
- Clear cache if issues persist  

---

## Version Information

- **Current Version**: 1.0  
- **Last Updated**: 19/01/2026 
- **Author**: David S  
- **Copyright**: ©2026 David S all rights reserved

