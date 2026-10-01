# Aloha Social logo files

The "@ stamen hibiscus" mark. All text is converted to outlines, so the SVGs look the same everywhere without needing the Fredoka font installed.

## Colors
- Coral `#E8604C` (flower)
- Deep sea `#0F4C5C` (wordmark, one-color version)
- Sand `#FBF4EA` (backgrounds)

## Which file where

**Website**
- `svg/logo-horizontal.svg` for the header on light backgrounds
- `svg/logo-horizontal-on-dark.svg` for dark footers and dark mode
- `svg/favicon.svg`, `png/favicon.ico`, `png/apple-touch-icon-180.png`

```html
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="icon" href="/favicon.ico" sizes="48x48">
<link rel="apple-touch-icon" href="/apple-touch-icon-180.png">
```

**App**
- iOS / App Store: `png/app-icon-1024.png` (square, no transparency; iOS rounds the corners itself)
- Google Play listing: `png/app-icon-512.png`
- Android adaptive icon: `svg/android-adaptive-foreground.svg` + `svg/android-adaptive-background.svg` (import both in Android Studio's Image Asset tool; the mark sits inside the safe zone)
- In-app mark: `svg/mark.svg`

**GitHub**
- Org or repo avatar: `png/github-avatar-500.png`
- Social preview (Settings > General > Social preview): `png/github-social-preview-1280x640.png`
- README header:

```markdown
<p align="center"><img src="assets/logo-horizontal.svg" alt="Aloha Social" height="80"></p>
```

**One-color uses** (stamps, merch, single-ink print)
- `svg/mark-mono-deep.svg` on light backgrounds, `svg/mark-mono-white.svg` on dark ones. The @ is cut out, so the background shows through.

## Notes
- Give the logo breathing room of at least a quarter of the flower's width on every side.
- Below about 32px the @ gets too small to read and the mark reads as a simple flower. That's fine for favicons.
- The wordmark uses Fredoka Bold (SIL Open Font License).
