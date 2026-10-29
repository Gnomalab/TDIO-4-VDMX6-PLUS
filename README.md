# TDIO for VDMX6 Plus

A collection of TouchDesigner components and effects by Gnomalab, prepared for use with **VDMX6 Plus** through TDIO.

> **Status:** work in progress. Install steps and the demo video link below are being completed.

---

## Contents

| Folder / file | What it is |
|---|---|
| `GN_feedbackEdge/` | Feedback effect with edge detection (`.tox` + preview PNG) |
| `Gn_8_Bits/` | 8-bit style processing effect (`.tox` + preview PNG) |
| `Gn_Neuromium_0.tox` | Experimental component |
| `Gn_Noise.tox` | Noise generator component |
| `Gn_VORONI_FLUIDS_V1.2.zip` | Voronoi fluid effect, V1.2 (contains `.tox` and preview PNG) |
| `TDTextGenByGnomlab/` | Text generator for VDMX6 Plus: `.tox`, `.toe` project and preview PNG |

---

## Requirements

- **VDMX6 Plus** (macOS).
- **TouchDesigner** with an Education, Commercial or Pro license installed on the same computer. Non-commercial licenses will not work.
- *[TouchDesigner version to be confirmed.]*

---

## Installation

1. Download or clone this repository.
2. Unzip `Gn_VORONI_FLUIDS_V1.2.zip` if you want to use the Voronoi fluid effect.
3. Open the VDMX assets folder. In VDMX, use **Help → Open Assets Folder in Finder**, or go to `~/Library/Application Support/VDMX/`.
4. Create a folder called `TouchDesignerFX` inside the assets folder if it does not exist yet.
5. Copy the `.tox` files you want into `TouchDesignerFX`.
6. The effects appear in VDMX immediately. You can preview them in the Workspace Inspector's **Assets** tab, or add them to a layer.

**Notes**
- After editing a `.tox`, remove and add the asset again, or restart VDMX.
- Each effect must follow the Image Filter protocol: it needs a top-level `inputImage` (inTOP) and `outputImage` (outTOP).

---

## Demo

*[Demo video link to be added. The video will be published on YouTube.]*

---

## Notes

- Effects come with preview images in their folders.
- `.toe` and `.tox` files are TouchDesigner files and need TouchDesigner to open.

---

## License

MIT License. See [LICENSE](LICENSE) for details.

---

## Credits

- **Author:** Gnomalab
- **Web:** [www.gnomalab.es](http://www.gnomalab.es/)
- **Instagram:** [@gnomalab](https://www.instagram.com/gnomalab)
- **YouTube:** [Gnomalab](https://www.youtube.com/@gnomalab)
