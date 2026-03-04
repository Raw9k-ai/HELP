# ⭐ File Tools — You're Doing Amazing!

> *Made with love for someone who deserves every shortcut in the world.*

This is a tiny, private little website I built for my close friend — because she was juggling a dozen different websites just to do everyday file tasks, and she deserved something that put it all in one place, worked on her phone, and never judged her for asking "wait, which website was it again?"

No sign-ups. No ads. No uploads to any server. Just open it and it works.

---

## 🛠 What's Inside

### 🖼 JPG / PNG Compressor
Shrink photos before sending them on WhatsApp, uploading to a portal, or emailing. Drag in one or many images, pick a quality level, and download smaller versions instantly.

### 📄 PDF Compressor
Make PDF files smaller without losing too much quality. Useful for portals that reject files over 1 MB. Drag in your PDF, adjust the image quality slider, and get a lighter file back.

### ✏️ File Renamer
Need to rename a file before downloading? Drop any file here, type the new name, and download it with the right name. Works for PDFs, images, Word docs — anything.

### 🔄 JPG / PNG → PDF Converter
Turn one or more photos into a single PDF, one image per page. Great for scanning documents with your phone camera and sending them as a PDF. Drag images in, pick a page size, convert.

### 💛 Indian Government Form Helper
Ever stared at a government form and had no idea what to write in a field? This tool explains every field in plain, simple English — like a friend sitting next to you. Tap a common form name or type any form name. Uses a free AI (OpenRouter) — requires internet and a free API key.

### 🪪 ID Photo & Signature Resizer
Resize a photo or signature to the exact pixel dimensions that government portals demand. Pick a preset (Passport, Aadhaar, PAN, UPSC, Driving Licence…) or type your own dimensions. Crop, pick a background colour, and download.

---

## 📱 Works on Mobile

Everything was built with Android and iPhone in mind. No app to install — just open the link in your browser and use it like any other website.

---

## 🔒 Your Files Never Leave Your Device

Every single tool — compression, conversion, resizing, renaming — runs entirely inside your browser using JavaScript. Your files are never sent to any server. Not even to mine.

The only exception is the **Form Helper**, which sends the form name (not your files) to an AI service to generate the explanation. Your documents are never shared.

---

## 🌐 Does It Work Offline?

**Almost entirely.** Once the page has loaded, the compressors, converter, renamer, and resizer all work without internet.

The **Form Helper** requires an internet connection to call the AI.

The page also loads fonts from Google Fonts on the first visit — after that, your browser caches them.

---

## 🚀 How to Use

Just open the GitHub Pages link in any browser. No installation, no account, no setup.

If you want to use the Form Helper, you'll need a free API key from [openrouter.ai](https://openrouter.ai) — it takes about one minute to set up and costs nothing.

---

## 💌 A Note

This was built as a personal gift — a quiet little corner of the internet where everything you need is already there, nothing is asking for your email, and the page literally tells you you're doing amazing.

Because you are. 🌟

---

## 🧰 Tech Used

- Vanilla HTML, CSS, and JavaScript — no frameworks, no build step
- [pdf-lib](https://pdf-lib.js.org/) — PDF creation and compression
- [pako](https://github.com/nodeca/pako) — zlib decompression for PDF images
- [OpenRouter](https://openrouter.ai/) — free AI API for the Form Helper
- Hosted on GitHub Pages

---

*All processing is done in your browser. Nothing is uploaded. No tracking. No cookies. Just tools that work.*
