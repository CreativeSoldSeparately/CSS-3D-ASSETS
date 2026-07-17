# CSS 3D Assets

A catalogue of `.glb` 3D models for use on the web. Every asset below has a stable, direct URL that can be dropped into a page (e.g. via [`<model-viewer>`](https://modelviewer.dev/)).

- **Machine-readable manifest:** [`assets.json`](assets.json) — name, category, path, direct URL, and byte size for every model.
- **Base raw URL:** `https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/`

## Usage on a website

```html
<script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/3.5.0/model-viewer.min.js"></script>

<model-viewer
  src="https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Products/Bang-Olufsen/Beosound%202.glb"
  camera-controls auto-rotate ar
  style="width:100%;height:500px">
</model-viewer>
```

> **CDN note:** raw.githubusercontent.com serves all files (up to 100 MB) with permissive CORS. For a faster CDN you can swap the host for `https://cdn.jsdelivr.net/gh/CreativeSoldSeparately/CSS-3D-ASSETS@main/` — but jsDelivr rejects files over 50 MB, so **Beolab-28.glb** and **Beosound_28_Middle bit.glb** must stay on the raw URL.

## Asset catalogue

### People

| Model | Size | Direct URL |
|---|---|---|
| `Abby Model` | 4.2 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/People/Abby%20Model.glb) |
| `Cole First Draft` | 13.4 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/People/Cole%20First%20Draft.glb) |
| `Jeremy First Draft` | 10.5 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/People/Jeremy%20First%20Draft.glb) |
| `Spenny First Draft` | 14.5 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/People/Spenny%20First%20Draft.glb) |

### Products

| Model | Size | Direct URL |
|---|---|---|
| `Beolab-28` | 79.7 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Products/Bang-Olufsen/Beolab-28.glb) |
| `Beosound 2` | 9.6 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Products/Bang-Olufsen/Beosound%202.glb) |
| `Beosound_28.First` | 5.6 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Products/Bang-Olufsen/Beolab-28-Exploded/Beosound_28.First.glb) |
| `Beosound_28_Middle bit` | 68.4 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Products/Bang-Olufsen/Beolab-28-Exploded/Beosound_28_Middle%20bit.glb) |
| `Beosound_28_end bit` | 8.7 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Products/Bang-Olufsen/Beolab-28-Exploded/Beosound_28_end%20bit.glb) |
| `Rebranded_Todo` | 9.5 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Products/Todo-Bein/Rebranded_Todo.glb) |

### Projects

| Model | Size | Direct URL |
|---|---|---|
| `BBC_TV` | 12.6 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Projects/BBC/BBC_TV.glb) |
| `BXR DOG` | 41.0 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Projects/BornXRaised/BXR%20DOG.GLB) |
| `MAC_BOOK MOCK UP BRIGHT MARK` | 9.5 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Projects/Brightmark/MAC_BOOK%20MOCK%20UP%20BRIGHT%20MARK.glb) |
| `Inked-Magazine-Nyjah-Cover` | 4.7 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Projects/Inked-Mag/Inked-Magazine-Nyjah-Cover.glb) |
| `Travis-Scott` | 35.1 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Projects/Travis-Scott/Travis-Scott.glb) |
| `vhs-tape-vice` | 4.5 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Projects/Vice/vhs-tape-vice.glb) |
| `van_game_asset_watt` | 9.2 MB | [link](https://raw.githubusercontent.com/CreativeSoldSeparately/CSS-3D-ASSETS/main/Projects/Watt-integration/van_game_asset_watt.glb) |
