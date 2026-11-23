## Vin Vin's Studio v3.8.2 — Studio Pro v2 Cutout & Edge Matting

### Cutout & Edge Quality Upgrades (Website, Windows Desktop & Android)
- **2048px Native Sub-Pixel Matting & Catmull-Rom Bicubic Upsampling**: Upgraded portrait cutout compositing to full `2048px` native RGB resolution with monotone-clamped Catmull-Rom bicubic mask upsampling and `1920px` Q96 pre-inference uploads.
- **Fast 3×3 Full-Covariance RGB Color-Line Guided Filter**: Replaced single-channel grayscale edge guidance with a 3×3 symmetric RGB Color-Line Guided Filter (He et al. / He & Sun) evaluated against native full-res pixels so fine hair wisps, ears, jawlines, collars, and iso-luminant color boundaries snap cleanly.
- **Wavefront Closed-Form Color Unmixing & Ghost-Island Filter**: 16-step BFS wavefront foreground/background propagation + closed-form alpha color unmixing (`F = (I - (1 - a)*B) / a`) eliminates white/colored halo fringes on hair strands and shoulders across all ID backdrop colors, while Chamfer-distance core filtering removes stray detached background smudges.
- **Upgraded Multi-Engine Neural RMBG Pipeline & Colored Formal Backdrops**: Fixed `BiRefNet RMBG` (`/image` endpoint), added `BRIA RMBG-3.0` fallback, enabled direct residential-IP CORS + server proxy routing, and added cached white-decontaminated studio matting when applying colored backgrounds behind Formal Attire portraits.
