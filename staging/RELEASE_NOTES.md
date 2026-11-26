## Vin Vin's Studio v3.8.10 (Android) — Compact Camera Dropdowns & Lifted Capture Deck

### Built-In Studio Camera Layout Fixes
- **Lifted Ergonomic Capture Button (Zero Bottom Clipping)**: Switched the camera dialog window to `decorFitsSystemWindows = true` with `safeDrawingPadding()` and a structured 3-zone layout (**Compact Top Bar** | **Dedicated Viewfinder** | **Lifted Bottom Capture Deck** with `36dp` bottom clearance), keeping Shutter, Gallery, and Flip comfortably positioned in the natural thumb zone above the system bar on every Android phone.
- **Compact Single-Row Dropdown Menus (Zero Left/Right Clipping)**: Consolidated multi-option camera tools into 3 crisp, compact dropdowns in a single non-scrolling top row:
  - **Crop Dropdown** (`3:4 ▾`): `Full Frame`, `2×2 / 1×1 Square`, `Passport (35×45 mm)`, `Studio Portrait (3:4)`, `Signature Box (5:2)`.
  - **Quality & Hardware ISP Dropdown** (`UHD · 12MP ▾`): Resolution presets (`Ultra HD Max Sensor`, `HD 2K`, `Fast`) + device-supported OEM Hardware Extensions (`Auto`, `HDR`, `Night`, `Face Retouch`, `Portrait Bokeh`).
  - **Tools Dropdown** (`Tools ▾`): Compact segmented controls for **Flash & Torch Fill Light** (`Off · Auto · Flash · Torch`), **Framing Guide** (`ID · 3×3 · Off`), **Self-Timer** (`Off · 3s · 5s`), **Exposure (EV) Slider** toggle, and **Front Selfie Mirror**.
- **Slimmer Viewfinder Overlays**: Compact `36dp` EV slider (with 1-tap `✕` hide button), compact `28dp` Zoom stop pill bar, compact labeled circular `Gallery` & `Flip` buttons symmetrically flanking the `66dp` Shutter ring, and a compact Crop Ratio dropdown on the instant Review & Crop screen.

### Release File
- **Android APK (`arm64-v8a`, `armeabi-v7a`, `x86_64`)**: `VinVinsStudio-v3.8.10-release.apk`
