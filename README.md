# Monet's Water Lilies — Chrome Theme

A soft, nature-inspired Google Chrome theme drawing its palette from Claude Monet's *Water Lilies*: muted pond greens, pale sage, and quiet botanical tones.

## Preview image

The New Tab Page background is loaded from:

`images/theme_ntp_background.png`

Add your chosen Water Lilies image at that exact path and filename. Use a high-resolution PNG (ideally at least 1920 × 1080) so it stays crisp on larger screens. Keep the main visual subject near the center because browser shortcuts may cover part of the image.

## Install locally

1. Clone or download this repository.
2. Add your image as `images/theme_ntp_background.png`.
3. Open `chrome://extensions` in Google Chrome.
4. Turn on **Developer mode**.
5. Select **Load unpacked** and choose this repository folder.

To remove it, open **Manage extensions** and select **Remove** on the theme. Your search engine setting (including Yahoo) is separate and will not be changed by this theme.

## Publish on the Chrome Web Store

1. Make sure the image file is included in the project.
2. Create a ZIP of the project contents, with `manifest.json` at the ZIP root (not inside an extra parent folder).
3. Register in the [Chrome Web Store Developer Dashboard](https://chrome.google.com/webstore/devconsole).
4. Upload the ZIP, add screenshots and listing details, choose public visibility, and submit it for review.

Google may require a one-time developer registration fee. Review the current dashboard requirements before submitting.

## Artwork and attribution

Claude Monet's original paintings are generally in the public domain, but a particular photograph or digital reproduction can have its own copyright or licensing terms. Use an image you have permission to redistribute, and add its source/credit here if required.

## Project structure

```
chrome-theme-/
├── manifest.json
├── README.md
└── images/
    ├── .gitkeep
    └── theme_ntp_background.png   # add your image here
```

## License

The theme configuration in this repository is provided under the MIT License. This does not grant rights to any third-party artwork added to the `images/` folder.
