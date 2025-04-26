*Noto Emoji with Catalan flag*

1. It seems Google is not intending to add flags of Regions in Spain: <https://github.com/googlefonts/noto-emoji/pull/352>
2. This modification is for personal use, more specifically, to display a Catalan flag in KDE's keyboard layout indicator <https://github.com/saeziae/xkb-catalan>, so there is country code CT as an alias, which is NOT standard.
3. Put the file [NotoColorEmoji.ttf](fonts/NotoColorEmoji.ttf) in `/usr/local/share/fonts/`, it should be able to override.

---

![Noto](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2Fab4b4276-9bb0-42a6-a675-510fcb6055df_1940x1088.png)
# Noto Emoji
Noto Emoji (Stands for No Tofu) is an open source (Open Font License 1.1) emoji library that provides standard Unicode emoji support and tools for working with them including:

- A Unicode compliant color emoji [font](https://github.com/googlefonts/noto-emoji/raw/main/fonts/NotoColorEmoji.ttf).
- A full library of Noto color emoji font files including vector svgs and pngs
- [Metadata](https://github.com/googlefonts/emoji-metadata) for Emoji Input (including shortcodes, emoji ordering, ascii equivalents)

## Color Font

The latest font file is found [here](https://github.com/googlefonts/noto-emoji/raw/main/fonts/NotoColorEmoji.ttf). If you want to download a specific version, please look at the gh-pages branch, where you will find the built assets for both our latest and older versions. 

## Monochrome Font

The black-and-white emoji font is back under active development and is available as a [variable font](https://fonts.google.com/noto/specimen/Noto+Emoji)

## Using NotoColorEmoji

NotoColorEmoji uses the CBDT/CBLC color font format, which is supported by Android
and Chrome/Chromium OS.  Windows supports it starting with Windows 10 Anniversary
Update in Chrome and Edge.  On macOS, only Chrome supports it, while on Linux it will
support it with some fontconfig tweaking, see [issue #36](https://github.com/googlei18n/noto-emoji/issues/36). Currently we do not build other color font formats.

## A note about PNGs

The assets provided in the repo are all those used to build the NotoColorEmoji font. With one exception: the flag images in the font are PNG images to which transforms have been applied to standardize the size and generate the wave and border shadow. We do not have SVG versions that reflect these transforms.

## License

Emoji fonts (under the fonts subdirectory) are under the
[SIL Open Font License, version 1.1](fonts/LICENSE).<br/>
Tools and most image resources are under the [Apache license, version 2.0](./LICENSE).
Flag images under third_party/region-flags are in the public domain or
otherwise exempt from copyright ([more info](third_party/region-flags/LICENSE)).

## Contributing

Please read [CONTRIBUTING](CONTRIBUTING.md) if you are thinking of contributing to this project.
