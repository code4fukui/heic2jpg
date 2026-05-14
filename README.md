# heic2jpg

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, in-browser tool to convert HEIC/HEIF images to JPEG. All processing is done on your device; your files are never uploaded to a server.

## Demo

[https://code4fukui.github.io/heic2jpg/](https://code4fukui.github.io/heic2jpg/)

## Features

-   **Client-Side Conversion:** Converts HEIC files to JPEG directly in your web browser. Your privacy is protected as no files are sent to a server.
-   **Batch Processing:** Drag and drop multiple HEIC files to convert them all at once.
-   **Multi-Image Support:** Correctly handles HEIC containers with multiple images.
-   **Automatic ZIP Download:** When multiple images are converted, they are automatically downloaded as a single `.zip` archive.
-   **Image Resizing:** Set a maximum width or height to resize images while maintaining aspect ratio.
-   **Adjustable Quality:** Control the compression level of the output JPEG files.
-   **Color Space Management:** Option to force conversion from Display-P3 to the more widely compatible sRGB color space.

## How to Use

1.  Open the [heic2jpg demo page](https://code4fukui.github.io/heic2jpg/).
2.  Drag and drop one or more `.heic` files onto the drop zone.
3.  (Optional) Adjust the conversion settings:
    *   **Max width/height (px):** Sets the maximum dimension for output images (default: `1220`).
    *   **Quality (0-1.0):** Adjusts the JPEG quality (default: `0.9`).
    *   **Force sRGB:** Check to convert the color space to sRGB.
4.  The conversion begins immediately. Your file(s) will be downloaded automatically once processing is complete.

## Requirements

-   A modern web browser.

## Acknowledgements

This application was created by Taisuke Fukuno ([@taisukef](https://twitter.com/taisukef)) as part of the [一日一創 (One Day One Creation)](https://fukuno.jig.jp/4230) project.

## License

MIT License — see [LICENSE](LICENSE).