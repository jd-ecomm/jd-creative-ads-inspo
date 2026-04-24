# JD Sports Canada — Meta Ads Creative Reference Library

A browsable library of 35 Meta ad inspiration assets, each rendered inside an iPhone + IG Reels frame to show how the ad would look in-feed.

## How to use

1. **Unzip the folder** — keep all files together (`index.html`, `/videos`, `/images`, `/assets`, `_data.js`).
2. **Double-click `index.html`** to open in your browser. Videos should autoplay in their iPhone frames as you scroll.

### If videos don't autoplay (tap-to-play fallback)

Some browsers block autoplay on local `file://` files. If that happens:
- **Just click any iPhone frame** — a yellow play button overlay appears, and tapping plays the video. The overlay disappears once playback starts.
- Autoplay will continue working for the rest of the session.

### For the cleanest experience — host it

The reference library is designed to be hosted so the whole creative team can browse it via a single URL. **Recommended hosts:**

- **Netlify Drop** (free, 30 seconds): Go to app.netlify.com/drop, drag the unzipped folder onto the page, done. You get a public URL to share.
- **Internal web server / SharePoint site that serves HTML**: upload the folder, link `index.html`.

## Two views

- **Grid Gallery** — filterable grid. Videos autoplay as you scroll past them (muted, looping). Good for browsing and comparing.
- **Reels Experience** — full-screen vertical scroll, one asset per screen, snap-scrolls like the real Reels UX. Good for pitching and showing "how it lands in-feed."

## Filters

Four filter groups, multi-select:
- **Brand / Inspiration Source** — which brand the ad is from (Dr Martens, Foot Locker, New Balance, StockX, Vans, Browns, Joe Hughes)
- **Style** — UGC, Studio, Interview
- **Format** — Unboxing, Speak to Camera, On Feet, POV, Multi-Product, Carousel, etc.
- **Type** — Video, Image, Carousel

Filters apply to both tabs. Clear All Filters resets everything.

## Folder structure

```
JD_Meta_Ads_Reference_Library/
├── index.html          ← Open this
├── _data.js            ← Asset catalogue
├── README.md           ← This file
├── assets/
│   └── jd-logo.png
├── videos/             ← 32 MP4s
└── images/
    ├── BrownsOnFeetPOV-IMG.jpg
    ├── JoeHughesShoes-POV-IMG.webp
    └── JoeHughes-Carousel/   ← 6 WEBPs, auto-cycled as carousel
```

## Adding new assets later

1. Drop the file into `/videos` or `/images`.
2. Open `_data.js` in any text editor, add an entry to `window.ASSETS` following the existing format. Copy an existing entry, change the filename/path/tags.
3. Save. Refresh. Done.

## Notes for the creative team

- Every asset is framed inside an iPhone with the IG Reels chrome (status bar, Reels label, right-rail icons, @jdsportscanada profile, Sponsored label, Shop Now CTA). This is to show "how it lands in-feed" — the chrome is visual context, not production-ready.
- Captions are placeholder — they exist to show caption placement, not to be used verbatim.
- The JD logo shows up as both the profile avatar and the right-rail brand thumb.
- Videos are muted by default (same as IG Reels behaviour).
- Tapping any iPhone force-plays that video.

---

Built for the JD Sports Canada creative team.
