# Bitsocial Assets

Official Bitsocial visual assets.

## License

The Bitsocial logo and banners in [assets/](assets/) are licensed under [Creative Commons Attribution-ShareAlike 4.0 International](assets/LICENSE.txt) (`CC-BY-SA-4.0`). You may use them commercially. When sharing the artwork, credit Bitsocial, link to the license, and indicate any changes. If you share an adaptation, license it under CC BY-SA 4.0 or a compatible license.

For an unmodified asset, you can use this credit.

> [Bitsocial artwork](https://github.com/bitsocialnet/assets) by Bitsocial, licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

The Bitsocial name and logo may function as project marks. Use of the artwork does not imply affiliation with or endorsement by Bitsocial.

Copies of the artwork previously distributed under GPL-3.0-or-later may still be used and redistributed under those terms. The [root GPL-3.0-or-later license](LICENSE) also covers repository code.

## Other project logos

Each project maintains its own logo. Follow the links for the artwork and its repository license.

| Project | Logo files | Repository license |
| --- | --- | --- |
| 5chan | [5chan logo](https://github.com/bitsocialnet/5chan/blob/master/public/assets/logo/logo-transparent.png) | [GPL-3.0-or-later](https://github.com/bitsocialnet/5chan/blob/master/LICENSE) |
| Seedit | [Sprout and wordmarks](https://github.com/bitsocialnet/seedit/tree/master/public/assets/sprout) | [GPL-3.0-or-later](https://github.com/bitsocialnet/seedit/blob/master/LICENSE) |
| Infinipedia | [Logo kit](https://github.com/bitsocialnet/infinipedia/blob/master/design/logo/README.md) | [GPL-3.0-or-later](https://github.com/bitsocialnet/infinipedia/blob/master/LICENSE) |
| ModelSwarm | [Vector logo](https://github.com/bitsocialnet/modelswarm/blob/master/public/logo.svg) | [GPL-3.0-or-later](https://github.com/bitsocialnet/modelswarm/blob/master/LICENSE) |

## Files

All distributable files live in [assets](assets).

### Logo

- `logo.svg` is the editable vector master for the logo exports.
- `logo-32.svg` is the 32 x 32 SVG icon export.
- `logo.ai` is a PDF-compatible vector export for Illustrator, generated from the SVG master. It contains vector paths and gradients, without a separate proprietary Illustrator editing payload.
- `logo.eps` is the EPS source export.

PNG logo exports are provided at `32`, `64`, `96`, `180`, `512`, `1024`, and `3000` pixels:

- `logo-transparent-*.png` has a transparent background.
- `logo-on-white-*.png` has a white background.
- `logo-on-black-*.png` has a black background.

### Banners

- `banner-wide-dark.*`
- `banner-wide-light.*`
- `banner-compact-dark.*`
- `banner-compact-light.*`

The `banner-*` files are the reusable hero/banner assets currently used by the Bitsocial web surfaces.

- `banner-mesh-wide-dark.*`
- `banner-mesh-wide-light.*`
- `banner-mesh-compact-dark.*`
- `banner-mesh-compact-light.*`

The `banner-mesh-*` files are background-only variants at the same sizes, showing just the polygon mesh from the Bitsocial websites in its fully active, glowing state.

## Export Notes

Logo PNGs and `logo-32.svg` were generated from `assets/logo.svg`.

AI and EPS exports were also generated from the SVG master. The flattened banner artwork was color-graded while preserving its framing, neutral network backgrounds, and alpha. Banner WebP exports are lossless.

The `banner-mesh-*` exports use bitsocial-web's `PolygonMeshBackground` mesh with its glow sweep frozen at full pointer speed, tuned for banners (smaller cells, more and brighter glowing segments), on the sites' white and black backgrounds.

Recommended defaults:

- Use `assets/logo-32.svg` for a 32 x 32 SVG icon request.
- Use `assets/logo-transparent-512.png` for general app icon previews.
- Use `assets/logo-transparent-3000.png` when a high-resolution raster source is needed.
