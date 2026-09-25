<p align="center">
  <a href="https://compresslyonline.blogspot.com/"><img src="logo.png" width="120" alt="Compressly logo"></a>
</p>

<h1 align="center">Compressly</h1>

<p align="center">
  <b>Free online image and PDF tools that run entirely in your browser.</b><br>
  No upload, no sign-up, no watermark.
</p>

<p align="center">
  <a href="https://compresslyonline.blogspot.com/"><b>Open Compressly →</b></a>
</p>

---

## Tools

| Tool | What it does |
|---|---|
| [Image Compressor](https://compresslyonline.blogspot.com/p/compress-image.html) | Compress JPG, PNG and WebP images, or hit an exact file size such as 100 KB, 50 KB or 20 KB |
| [Image Resizer](https://compresslyonline.blogspot.com/p/image-resizer.html) | Resize to 4K, 1080p, 720p or exact pixels such as 300 × 300 |
| [Image Converter](https://compresslyonline.blogspot.com/p/image-converter.html) | Convert between JPG, PNG and WebP (GIF, BMP and AVIF input) |
| [Background Remover](https://compresslyonline.blogspot.com/p/remove-background.html) | Remove the background from photos of people, products and pets with AI |
| [Image Upscaler](https://compresslyonline.blogspot.com/p/image-upscaler.html) | Enlarge images 2×, 3×, 4× or to 4K with edge sharpening |
| [Image to PDF](https://compresslyonline.blogspot.com/p/image-to-pdf.html) | Combine photos or scans into one PDF, in any order |
| [Text to PDF](https://compresslyonline.blogspot.com/p/text-to-pdf.html) | A document editor with headings, tables and images that saves as PDF or Word |
| [PDF to Text](https://compresslyonline.blogspot.com/p/pdf-to-text.html) | Extract the text from a PDF |
| [PDF to Word](https://compresslyonline.blogspot.com/p/pdf-to-word.html) | Turn the text of a PDF into an editable .docx |
| [Word to PDF](https://compresslyonline.blogspot.com/p/word-to-pdf.html) | Convert .docx documents to PDF |

## Why Compressly

- **Private.** Files are processed in your browser tab and are never uploaded to a server.
- **Target file size.** Pick a limit and Compressly searches for the highest quality that fits. This is useful for job applications, exam forms and email.
- **Batch processing.** Up to 30 images at once, downloaded one by one or as a ZIP.
- **Works on mobile.** Runs in any modern browser on phones and computers.
- **Free.** No account, no daily limit.

## How it works

Images are decoded and re-encoded with the browser's Canvas API. Target-size mode runs a binary search over the encoder quality. PNG output can be reduced to an optimised colour palette. The PDF and Word tools read and write the files directly in JavaScript. The background remover runs an open-source segmentation model ([ormbg](https://huggingface.co/onnx-community/ormbg-ONNX), Apache-2.0) locally through [Transformers.js](https://github.com/huggingface/transformers.js).

## Author

Built by [Sabbir Hossain](https://github.com/SabbirHossain-02).

**Website:** https://compresslyonline.blogspot.com/
