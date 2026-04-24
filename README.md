# MikesLaptopsAds

Simple fullscreen ad display for showroom laptops.

## What it does

- Rotates ads every 30 seconds by default
- Uses server time when available to keep displays aligned
- Falls back to local clock if offline
- Preloads images to avoid flicker
- Saves display settings in the browser

## Files

- [index.html](index.html) — slideshow and control panel
- [ads/](ads) — default ad images

## Default ads

The slideshow ships with:

- [ads/ad1.png](ads/ad1.png)
- [ads/ad2.png](ads/ad2.png)
- [ads/ad3.png](ads/ad3.png)
- [ads/ad4.png](ads/ad4.png)

## Controls

Open the panel with the Display settings button or Ctrl+Shift+A.

Available controls:

- Pause or resume playback
- Previous / next slide
- Change duration from 5 to 120 seconds
- Toggle fade transitions
- Switch fit mode between contain and cover
- Adjust brightness and contrast
- Toggle night dimming
- Add custom image URLs
- Reorder, preview, or remove custom ads
- Export or import settings
- Reload assets
- Clear saved settings

## Shortcuts

- Esc: close panel
- Ctrl+Shift+A: open or close panel
- Left / Right arrows: previous or next slide
- Space: pause or resume
- F: fullscreen

## Notes

- The default cycle is 30 seconds per ad.
- Custom ads are stored locally in the browser.
- For the best sync, host the page over HTTP or HTTPS rather than opening the file directly.