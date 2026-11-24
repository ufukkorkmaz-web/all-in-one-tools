# Toolbox

Open `index.html` in a modern browser. All tools are separate HTML pages.

## Homepage order

The first five entries remain fixed: Iframe Maker, QR Code Maker, PDF Toolkit, PPTX Media Extractor, Image to ASCII. The sixth card is the floating CSS Tools menu (Glassmorphism, Animation, Typography). New standalone tools appear after it.

## Metadata Remover

Open `metadata-remover.html` from the homepage. Supports batch JPEG, PNG, WebP and BMP input with PNG/JPEG/WebP output; strips embedded metadata by decoding and redrawing image pixels in the browser. Supports individual downloads and a ZIP of the cleaned images.

This can change quality, color information and size, and does not remove visible watermarks or text. It does not handle GIF animation, vector SVG, PDF, or TIFF. Files are never uploaded by this tool. Do not use it as a forensic guarantee of anonymity.

New tools:
- heic-converter.html — HEIC/HEIF to JPEG, PNG, WebP, processed in browser. Native decoding first; heic2any decoder is downloaded from jsDelivr if native decoding unavailable, requiring internet access but not uploading your photos.
- image-privacy-blur.html — Draw editable rectangular solid covers, pixelation, or blur over an image; undo/reset and export flattened PNG/JPEG/WebP. For privacy use solid covers, not blur.

Homepage: fixed order of the first five tools, CSS Tools floating menu, then Metadata Remover, HEIC Converter and Image Privacy Blur.
