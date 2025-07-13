# Chippy Corne ZMK Configuration

ZMK configuration for Corne (CRKBD) with Seeed Xiao BLE and Choc switches, optimized for coding and programming.

## Features

- **✨ Coding-Optimized**: Symbol layer designed for programming with easy access to brackets, operators, and numbers
- **🏠 Home Row Modifiers**: All modifiers accessible without moving hands from home position
- **🖱️ Vim-style Mouse Navigation**: hjkl movement with mouse clicks
- **⚡ Smart Combos**: Quick access to common shortcuts without layer switching
- **🎯 Single Base Layer**: Works seamlessly with both Mac and Windows

## Keyboard Layout

### Base Layer (Home Row Mods)
```
╭─────────────────────────────────────────────────╮
│ TAB │ Q │ W │ E │ R │ T │   │ Y │ U │ I │ O │ P │ BSPC│
├─────────────────────────────────────────────────┤
│CTRL/│GUI│ALT│SFT│CTL│ G │   │ H │CTL│SFT│ALT│GUI│  '  │
│ ESC │ A │ S │ D │ F │   │   │   │ J │ K │ L │ ; │     │
├─────────────────────────────────────────────────┤
│SHIFT│ Z │ X │ C │ V │ B │   │ N │ M │ , │ . │ / │SHFT/│
│     │   │   │   │   │   │   │   │   │   │   │   │ DEL │
├─────────────────────────────────────────────────┤
│     │   │ GUI │LOWER│SPACE│   │ENTER│RAISE│ ALT │     │
╰─────────────────────────────────────────────────╯
```

**Home Row Modifiers:**
- **A**: Tap=A, Hold=Gui/Cmd
- **S**: Tap=S, Hold=Alt  
- **D**: Tap=D, Hold=Shift
- **F**: Tap=F, Hold=Ctrl
- **J**: Tap=J, Hold=Ctrl
- **K**: Tap=K, Hold=Shift
- **L**: Tap=L, Hold=Alt
- **;**: Tap=;, Hold=Gui/Cmd

### Lower Layer (Numbers & Navigation)
```
╭─────────────────────────────────────────────────╮
│     │ 1 │ 2 │ 3 │ 4 │ 5 │   │ 6 │ 7 │ 8 │ 9 │ 0 │ BSPC│
├─────────────────────────────────────────────────┤
│     │F1 │F2 │F3 │F4 │F5 │   │ ← │ ↓ │ ↑ │ → │   │     │
├─────────────────────────────────────────────────┤
│     │F6 │F7 │F8 │F9 │F10│   │   │   │   │   │   │     │
├─────────────────────────────────────────────────┤
│     │   │   │     │     │   │   │   │   │     │     │
╰─────────────────────────────────────────────────╯
```

### Raise Layer (Coding Symbols)
```
╭─────────────────────────────────────────────────╮
│  `  │ ! │ @ │ # │ $ │ % │   │ ^ │ & │ * │ _ │ + │ DEL │
├─────────────────────────────────────────────────┤
│  ~  │ 1 │ 2 │ 3 │ 4 │ 5 │   │ 6 │ 7 │ 8 │ 9 │ 0 │  \  │
├─────────────────────────────────────────────────┤
│     │ ( │ ) │ [ │ ] │ { │   │ } │ = │ - │ | │ " │     │
├─────────────────────────────────────────────────┤
│     │   │   │     │     │   │   │   │   │     │     │
╰─────────────────────────────────────────────────╯
```

**Coding Optimizations:**
- **Brackets**: Easy access to `()`, `[]`, `{}` on home row
- **Numbers**: Accessible on both layers
- **Operators**: `=`, `-`, `+`, `*`, `_` well positioned
- **Special chars**: `|`, `"`, `\` for coding

### Mouse Layer (Vim Navigation)
```
╭─────────────────────────────────────────────────╮
│     │   │   │   │   │   │   │   │   │ ↑ │   │   │     │
├─────────────────────────────────────────────────┤
│     │   │   │   │   │   │   │ ← │ ↓ │ ↓ │ → │   │     │
├─────────────────────────────────────────────────┤
│     │   │   │   │   │   │   │   │M4 │M5 │   │   │     │
├─────────────────────────────────────────────────┤
│     │   │   │     │ LMB │   │ RMB │ MMB │   │     │     │
╰─────────────────────────────────────────────────╯
```

**Vim-style Navigation:**
- **h** (H position): Move left
- **j** (J position): Move down  
- **k** (K position): Move up
- **l** (L position): Move right
- **LMB/RMB/MMB**: Mouse buttons on thumbs

### Adjust Layer (System Controls)
```
╭─────────────────────────────────────────────────╮
│     │   │   │   │   │   │   │   │   │   │   │   │     │
├─────────────────────────────────────────────────┤
│BT_CLR│MAC│WIN│iPad│BT3│BT4│   │   │   │   │   │   │     │
├─────────────────────────────────────────────────┤
│BOOTL │   │   │   │   │   │   │   │   │   │   │   │BOOTL│
├─────────────────────────────────────────────────┤
│     │   │   │     │     │   │   │   │   │     │     │
╰─────────────────────────────────────────────────╯
```

## Combos Reference

### System & Navigation
| Combo | Keys | Action | Description |
|-------|------|--------|-------------|
| Spotlight | `LH0 + RH0` | Cmd + Space | App launcher |
| App Switcher | `A+S+D+F` | Cmd + Tab | Switch between apps |
| Mouse Layer | `LH1 + RH1` | Hold | Access mouse navigation |

### Text Editing (Work on any OS)
| Combo | Keys | Action | Description |
|-------|------|--------|-------------|
| Copy | `C+V` | Cmd + C | Copy selection |
| Paste | `V+B` | Cmd + V | Paste clipboard |
| Cut | `C+B` | Cmd + X | Cut selection |
| Undo | `Z+X` | Cmd + Z | Undo last action |
| Select All | `A+F` | Cmd + A | Select all text |
| Save | `A+S` | Cmd + S | Save file |
| Find | `S+D` | Cmd + F | Find in document |
| Close Window | `E+T` | Cmd + W | Close current window |

### Home Row Mod Examples
| Shortcut | Keys | Description |
|----------|------|-------------|
| Copy | `F + C` | Hold F (Ctrl) + tap C |
| Save | `A + S` | Hold A (Cmd) + tap S |
| Select Word | `D + →` | Hold D (Shift) + arrow |
| Switch Tab | `F + Tab` | Hold F (Ctrl) + Tab |

## Key Position Reference

```
╭─────────────────────────────────────────────────╮
│LT5 │LT4│LT3│LT2│LT1│LT0│   │RT0│RT1│RT2│RT3│RT4│RT5 │
├─────────────────────────────────────────────────┤
│LM5 │LM4│LM3│LM2│LM1│LM0│   │RM0│RM1│RM2│RM3│RM4│RM5 │
├─────────────────────────────────────────────────┤
│LB5 │LB4│LB3│LB2│LB1│LB0│   │RB0│RB1│RB2│RB3│RB4│RB5 │
├─────────────────────────────────────────────────┤
│    │   │   │LH2│LH1│LH0│   │RH0│RH1│RH2│   │   │    │
╰─────────────────────────────────────────────────╯
```

## Build & Installation

### Prerequisites
- [GitHub Account](https://github.com)
- Fork this repository
- Enable GitHub Actions

### Build Process

1. **Fork Repository**
   ```bash
   # Fork this repo to your GitHub account
   # Clone your fork locally
   git clone https://github.com/YOUR_USERNAME/zmk-config-corne-xiao-choc.git
   ```

2. **Enable Actions**
   - Go to your forked repository
   - Click "Actions" tab
   - Click "I understand my workflows, go ahead and enable them"

3. **Trigger Build**
   - Make any change to trigger build (edit README)
   - Commit and push changes
   - GitHub Actions will build firmware automatically

4. **Download Firmware**
   - Go to "Actions" tab in your repository
   - Click on the latest successful build
   - Download "firmware" artifact
   - Extract the ZIP file

### Flashing Firmware

**For Seeed Xiao BLE controllers:**

1. **Enter Bootloader Mode**
   - Connect keyboard via USB
   - Double-click reset button on Xiao BLE
   - Blue LED should pulse (bootloader mode)

2. **Flash Firmware**
   - Xiao will appear as USB drive "XIAO-SENSE"
   - Copy `chippy_left-seeeduino_xiao_ble-zmk.uf2` to left half
   - Copy `chippy_right-seeeduino_xiao_ble-zmk.uf2` to right half
   - Controllers will reboot automatically

3. **Pairing**
   - Both halves should connect automatically
   - If not, hold `ADJUST` layer → press `BT_CLR`

### Configuration Files

```
zmk-config-corne-xiao-choc/
├── config/
│   ├── chippy.keymap           # Main keymap configuration
│   ├── boards/shields/chippy/  # Shield definition
│   └── west.yml               # Dependencies
├── build.yaml                 # Build configuration  
└── README.md                  # This file
```

### Mouse Support Setup

**Enable in build.yaml:**
```yaml
---
include:
  - board: seeeduino_xiao_ble
    shield: chippy_left
    cmake-args: -DCONFIG_ZMK_POINTING=y
  - board: seeeduino_xiao_ble  
    shield: chippy_right
    cmake-args: -DCONFIG_ZMK_POINTING=y
```

### Bluetooth Setup

**Device Slots:**
- **Slot 0**: Mac/MacBook (press `MAC` on ADJUST layer)
- **Slot 1**: Windows PC (press `WIN` on ADJUST layer)  
- **Slot 2**: iPad/Tablet (press `iPad` on ADJUST layer)

**Pairing Process:**
1. Hold `LOWER + RAISE` to access ADJUST layer
2. Press desired device slot (MAC/WIN/iPad)
3. Keyboard enters pairing mode
4. Connect from device's Bluetooth settings

**Troubleshooting:**
- **Clear bonds**: `ADJUST` → `BT_CLR`
- **Reset**: `ADJUST` → `BOOTL` (both corners)

## Customization

### Modify Combos
Edit `config/chippy.keymap`, find combos section:
```c
combo_copy {         
    timeout-ms = <20>;
    key-positions = <LB3 LB2>;  // C + V keys
    bindings = <&kp LG(C)>;     // Cmd + C
};
```

### Add New Layer
1. Define layer number: `#define MYLAYER 5`
2. Add layer in keymap section
3. Add activation method (combo or key)

### Home Row Mod Timing
Adjust in behaviors section (if needed):
```c
&mt {
    tapping-term-ms = <200>;    // How long to hold for modifier
    quick-tap-ms = <175>;       // Prevent accidental holds
};
```

## License

MIT License - Feel free to modify and share!

## Credits

- Based on ZMK firmware
- Corne keyboard by foostan
- Optimized for Seeed Xiao BLE controllers
- Community contributions and feedback