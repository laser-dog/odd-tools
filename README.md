# ODD Tools

Static page of small web tools, live at https://toolkit.odd-enterprises.com. No build step, no dependencies — upload the folder as-is.

```
index.html                  Tools hub (landing page)
assets/                     Thumbnails for each tool
image-optimizer/index.html  PNG @1x/@2x + WebP optimizer (runs fully in the browser)
```

## Adding a tool
1. Create `your-tool/index.html`.
2. Add its thumbnail to `assets/`.
3. Copy the `<a class="tool">` block in `index.html` and edit it.

All links are relative, so it works from the domain root or a subfolder.
