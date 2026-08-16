# XMB Menu for EmulationStation-X

**XMB Menu ES-X** is a port and adaptation of the
[XMB Menu theme for ES-DE](https://github.com/anthonycaccese/xmb-menu-es-de),
bringing its PSP / PlayStation 3 inspired XrossMediaBar interface to
**EmulationStation-X**.

The original XML layout was created by **InitialDin** and was later
refactored and expanded for ES-DE by **Anthony Caccese**, who added
cleaner image assets, color schemes, customization support and additional
aspect ratios.

This version adapts the theme structure and visual elements to the
EmulationStation-X theme engine while attempting to preserve the look and
feel of the original project.

---

## Preview

<!-- Replace this image with a screenshot of XMB Menu ES-X -->

![XMB Menu ES-X](preview.png)

---

## Features

- XMB-inspired system carousel
- PSP / PlayStation 3 style interface
- Animated wave background
- System controller artwork
- Physical media artwork
- Game metadata display
- Vertical game carousel
- Game video and fanart support
- Clock display
- Network status indicator
- Navigation sounds
- EmulationStation-X Theme Options support
- Multiple background styles

---

## Theme Options

XMB Menu ES-X uses the **EmulationStation-X Theme Options system**.

The available background styles can be selected directly from the
Theme Options menu.

Current styles include:

- **Blue**
- **Orange**
- **Purple**
- **Red**
- **20th Anniversary**

The selected style is stored in `theme.ini`.

Example:

```ini
LAYOUT=blue

[layout]
type=select
label=Color del fondo - Color style
apply_to=layout
values=blue|Blue-Azul,orange|Orange-Naranja,purple|Purple-Violeta,red|Red-Rojo,20anniversary|20th Anniversary
default=blue