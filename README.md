# Load a Chrome Extension Locally

## 1. Open Chrome Extensions Page

Open:

chrome://extensions

---

## 2. Enable Developer Mode

Top right corner:

Developer mode → ON

---

## 3. Load the Extension

Click:

Load unpacked

Then select your extension folder.

Example:

my-extension/

---

## 4. Done

The extension is now loaded locally in Chrome.

You can:

- test it
- pin it
- edit files
- reload changes instantly

---

## Reload After Changes

After editing files:

1. Go to chrome://extensions
2. Click the reload icon on your extension

---

## Common Issues

### "Manifest file is missing"

Make sure the file is named exactly:

manifest.json

---

### Extension does not load

Check:

- valid JSON
- manifest_version is correct
- no missing files
- no extra commas

---

## Share With Others

Zip the extension folder and send it.

Other users can install it the same way using:

chrome://extensions → Load unpacked
