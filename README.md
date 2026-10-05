# Harbor for Jellyfin

A Jellyfin 12 theme that looks like DebridPlayer: charcoal surfaces, amber accent, Fraunces headings, light pill buttons, lifted poster cards. The video player has no header overlay; only the title and buttons remain.

## Install

Dashboard → General → Custom CSS code:

```css
@import url("https://cdn.jsdelivr.net/gh/luttman/harbor-jellyfin@main/Theme/harbor-jf12.css");
```

Hard-refresh the web client (Ctrl+F5) afterwards. jsDelivr caches `@main` for up to 12 hours; pin a commit or tag to update at once.

## Customise

All colours are variables at the top of `Theme/harbor-jf12.css` (`--h-brand`, `--h-bg`, `--h-card` …). The `--jf-palette-*` block maps them onto Jellyfin 12's MUI components.

Reference for the JF12 selectors: [ElegantFin JF12](https://github.com/mihaif7/elegantfin-jf12).
