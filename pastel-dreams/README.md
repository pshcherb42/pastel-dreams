# Pastel Dreams

A two-theme VS Code pack of cozy, dreamy pastel dark themes.

## Ghibli Dreams

Inspired by lofi Studio Ghibli-style dusk-in-the-forest scenes: muted indigo background, sage-green strings, dusty pink types, warm golden constants, and a soft lavender for keywords.

| Role | Hex | Feel |
|---|---|---|
| Background | `#2A2B3C` | Deep dusty indigo, like an overcast forest at dusk |
| Foreground | `#E8DFD3` | Warm cream |
| Comments | `#7C7A8C` | Muted lavender-grey |
| Keywords | `#C99FDE` | Soft lavender (evening sky) |
| Strings | `#B5D6B2` | Sage green (forest) |
| Functions | `#F2C6B4` | Soft peach/coral (sunset) |
| Numbers / constants | `#F0D8A8` | Warm gold (lantern light) |
| Variables | `#A8C6DE` | Dusty blue (sky) |
| Classes / types | `#E8B4BC` | Dusty pink (cherry blossom) |
| Errors | `#E09999` | Muted red |

## Kuromi Magic Shop

A pastel-goth palette in the same dreamy spirit: near-black purple background, hot-pink/magenta keywords, and soft lavender accents.

| Role | Hex | Feel |
|---|---|---|
| Background | `#1E1A26` | Near-black purple, like a dim little shop at night |
| Foreground | `#E8E0F0` | Soft lavender-white |
| Comments | `#6B5F7A` | Muted purple-grey |
| Keywords | `#E88AC4` | Hot magenta/pink |
| Strings | `#C9A8E0` | Soft lavender |
| Functions | `#9B6FBF` | Medium purple |
| Numbers / constants | `#F2C6E0` | Pale pink |
| Variables | `#B8A8D8` | Light purple |
| Classes / types | `#F2A8D0` | Bright pink |
| Errors | `#D06868` | Muted red |

## Garden Bloom (light)

A sunny garden palette: cream background, sage-green strings, mustard/gold constants, and coral-red keywords.

| Role | Hex | Feel |
|---|---|---|
| Background | `#FBF9F1` | Soft cream |
| Foreground | `#3A3F2E` | Dark olive |
| Comments | `#A8A890` | Muted sage-grey |
| Keywords | `#C0392B` | Coral red |
| Strings | `#5C7A4A` | Deep sage green |
| Functions | `#B5711E` | Warm mustard |
| Numbers / constants | `#C48A1E` | Golden yellow |
| Variables | `#4A5F3A` | Forest green |
| Classes / types | `#A8461E` | Burnt orange |
| Errors | `#C0392B` | Red |

## Blue Bloom (light)

A soft blue floral palette: pale blue background, dusty rose keywords, and slate-blue variables.

| Role | Hex | Feel |
|---|---|---|
| Background | `#F5F9FC` | Pale sky blue |
| Foreground | `#2E3A47` | Deep slate blue |
| Comments | `#A0B4C4` | Muted blue-grey |
| Keywords | `#C0524A` | Muted coral |
| Strings | `#3A6E93` | Deep blue |
| Functions | `#2E6690` | Ocean blue |
| Numbers / constants | `#B58A26` | Warm gold |
| Variables | `#4A5F70` | Slate blue |
| Classes / types | `#A8506E` | Dusty rose |
| Errors | `#C0524A` | Muted red |

## Ghibli Bloom (light)

A hybrid: Garden Bloom's cream background and warm UI structure, with Ghibli Dreams' color family (lavender/sage/peach/gold/dusty blue/rose) carried over for syntax highlighting — each hue deepened just enough to stay readable on a light background.

| Role | Hex | Feel |
|---|---|---|
| Background | `#FBF9F1` | Soft cream (from Garden Bloom) |
| Foreground | `#40453A` | Warm charcoal-olive |
| Comments | `#9B9483` | Muted taupe |
| Keywords | `#8B5FA8` | Deep lavender |
| Strings | `#5C7A4A` | Sage green |
| Functions | `#C77B54` | Deep coral/peach |
| Numbers / constants | `#B8860B` | Warm gold |
| Variables | `#4A6C8A` | Deep dusty blue |
| Classes / types | `#A8506E` | Deep dusty rose |
| Accent (status bar) | `#B8607A` | Dusty rose |

## Dusk Bloom (in-between)

A twilight mix of all five: a mid-tone blue-violet background — darker than the light Blooms, lighter than Ghibli/Kuromi's full dark — with a bright blue accent (status bar, functions) and Kuromi's hot magenta as the "edge" color for keywords and cursor.

| Role | Hex | Feel |
|---|---|---|
| Background | `#3D4460` | Twilight blue-violet, neither dark nor light |
| Foreground | `#EAE6F2` | Pale lavender-white |
| Comments | `#8B8FAE` | Muted blue-grey |
| Keywords | `#E88AC4` | Kuromi magenta (the edge) |
| Strings | `#A8D4C9` | Blue-green sage |
| Functions | `#7FB8E0` | Bright sky blue |
| Numbers / constants | `#F0D8A8` | Warm gold |
| Variables | `#A8C6DE` | Dusty blue |
| Classes / types | `#C9A8E0` | Soft lavender |
| Accent (status bar) | `#6FA8C9` | Ocean blue |

## Try it locally (no publishing needed)

1. Copy this whole `ghibli-dreams` folder into your VS Code extensions directory:
   - macOS/Linux: `~/.vscode/extensions/`
   - Windows: `%USERPROFILE%\.vscode\extensions\`
2. Restart VS Code.
3. `Cmd/Ctrl+Shift+P` → "Preferences: Color Theme" → select **Ghibli Dreams**, **Kuromi Magic Shop**, **Garden Bloom**, **Blue Bloom**, **Ghibli Bloom**, or **Dusk Bloom**.

## Publish to the VS Code Marketplace (for your portfolio)

1. Install the packaging CLI:
   ```
   npm install -g @vscode/vsce
   ```
2. Create a publisher on the [Marketplace management page](https://marketplace.visualstudio.com/manage) and update the `"publisher"` field in `package.json` to match.
3. Add a 128x128 `icon.png` to this folder and re-add `"icon": "icon.png"` to `package.json`.
4. Package it:
   ```
   vsce package
   ```
   This produces a `.vsix` file you can install locally or attach to your portfolio/GitHub release.
5. Publish it:
   ```
   vsce publish
   ```

## For your portfolio page

Good things to show alongside this:
- A before/after screenshot or short screen-recording of a real code file (e.g. a Python or JS snippet) rendered in the theme.
- The Marketplace listing link once published.
- A one-line pitch: *"A pastel dark-theme pack for VS Code — designed and shipped end-to-end, from color theory to Marketplace publishing."*

## License

MIT
