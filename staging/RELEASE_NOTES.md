## Vin Vin's Studio v3.8.9 — Web, Windows Desktop & Android

### Cleaner Dropdown Selectors & Separated Buttons (Web, Windows & Android)
- **Smart Dropdown Menus**: Replaced dense multi-option button grids with crisp Liquid-Glass dropdown selectors for **Photo Size** (+ quick favorite pills), **Paper Size** (paired cleanly with Margins), **Export Format**, **AI Attire**, **AI Engine**, **Formal Style**, and **Edit Photo** controls (Background preset, Name Layout Style & Font, Signature Pen Width, Extracted Ink, and Snap Placement).
- **Purpose-Separated Actions**: Organized the TopBar into logical groups with subtle dividers (`App` | `History · Updates · Bug` | `API Keys · Theme · Login`) and visually separated primary, edit/utility, and danger-tinted destructive actions (`Clear`, `Clear Page`, preset delete).
- **Zero Duplicate Controls & Balanced Mobile Layout**: Hid redundant Upload Photo CTA when empty and made mobile Web & Android bottom trays hug their content so the portrait workspace has maximum breathing room.

### Pro Built-In Studio Camera (Android Exclusive)
- **Adaptive Portrait & Landscape Layouts**: Responsive `BoxWithConstraints` controls that automatically adapt for compact portrait phones (`<380dp`), standard portrait, and landscape orientation (moving Shutter, Flip, and Gallery to a dedicated side capture rail so buttons never crowd or overlap the viewfinder).
- **Live Crop Layout + Interactive Review Crop & Rotate**: Selectable live crop masks (`Full Frame`, `2×2 ID 1:1`, `Passport 35×45`, `3:4 Portrait`, and `Signature 5:2`) with darkened outer scrim, corner brackets, and centered guides. On the instant review screen, switch crop ratios, pinch-to-zoom & drag to reframe, or rotate 90° before cropping from the full-resolution capture.
- **Ultra HD & Native Android Camera Capabilities**:
  - **Ultra HD (Max Sensor)** quality selector using CameraX `HIGHEST_AVAILABLE_STRATEGY` + `CAPTURE_MODE_MAXIMIZE_QUALITY` + 98% JPEG, with a live hardware **MP badge** queried from Camera2 `CameraCharacteristics` (alongside `HD 2K` and `Fast` presets).
  - **Hardware OEM CameraX Extensions**: Dynamically detects and exposes native device **HDR**, **Night**, **Face Retouch**, and **Portrait Bokeh** ISP modes with automatic safe fallback.
  - **Pro Controls**: Continuous **Torch** studio fill light (inside Flash toggle), **Exposure (EV) slider**, **Pinch-to-Zoom** + dynamic optical/digital zoom stops (including ultra-wide `0.6×` when supported), **ID Guide / 3×3 Rule-of-Thirds Grid / Off**, self-timer (`3s`/`5s`), and Front Mirror toggle.

### Release Files
- **Windows Installer (`x64`)**: `VinVinsStudio-Setup-3.8.9.exe`
- **Windows Portable (`x64`)**: `VinVinsStudio-Portable-3.8.9.exe`
- **Android APK (`arm64-v8a`, `armeabi-v7a`, `x86_64`)**: `VinVinsStudio-v3.8.9-release.apk`
