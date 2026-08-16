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

<table>
  <tr>
    <td>
      <img width="1366" height="768"
           alt="Captura de pantalla_2026-08-15_21-42-27"
           src="https://github.com/user-attachments/assets/aa0485b0-979c-4f29-88d0-c9bd568048d3" />
    </td>
    <td>
      <img width="1366" height="768"
           alt="Captura de pantalla_2026-08-15_21-43-12"
           src="https://github.com/user-attachments/assets/767a442c-da07-425d-82de-e8ba34324e15" />
    </td>
  </tr>
  <tr>
    <td>
      <img width="1366" height="768"
           alt="Captura de pantalla_2026-08-15_21-44-45"
           src="https://github.com/user-attachments/assets/b15d3a2a-7b20-4628-b492-a018a58990d0" />
    </td>
    <td>
      <img width="1366" height="768"
           alt="Captura de pantalla_2026-08-15_21-45-46"
           src="https://github.com/user-attachments/assets/3411be97-6830-49d6-8234-aebbcc871364" />
    </td>
  </tr>
</table>


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
