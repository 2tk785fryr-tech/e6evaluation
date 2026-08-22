# ITG E-6 Brag Sheet & Eval Prompt Builder

A single-page tool for ITG First Class Petty Officers (MMN1 / EMN1 / ETN1) to document a reporting period and generate a prompt for drafting NAVPERS 1616/26 Block 43 comments.

Nothing is uploaded anywhere. Everything runs in the browser on the user's own device.

---

## Files

| File | What it is |
|---|---|
| `index.html` | The tool. This is what everyone uses. |
| `demo.html` | Same tool, prefilled with fictional sample data for testing. Not for distribution. |
| `prompt-template.md` | Text-only version of the prompt, for anyone who'd rather work in a document. |
| `manifest.json`, `icon-*.png`, `apple-touch-icon.png` | Home-screen icon and app metadata. |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is. |

---

## Turning on GitHub Pages

1. Upload every file in this folder to the repository root (**Add file → Upload files**, drag them all in, **Commit changes**).
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**.
4. Branch: **main**, folder: **/ (root)**. Click **Save**.
5. Wait 1–2 minutes. The URL appears at the top of that same page:

```
https://2tk785fryr-tech.github.io/e6evaluation/
```

That link is what you send out. It works on any phone, tablet, or computer with no download and no install.

To check the demo version: add `demo.html` to the end of the URL.

---

## Why hosting matters

Two features only work over HTTPS, which is what Pages provides:

- **Copy button** — the browser clipboard API is blocked on locally-opened files.
- **Autosave** — work is saved on the user's own device as they type, so closing the tab doesn't lose it.

Opened as a downloaded file, the tool still works, but users have to select-and-copy by hand and lose their work if the tab closes.

---

## Add to Home Screen

Once it's hosted, users can install it like an app:

- **iPhone/iPad (Safari):** Share button → Add to Home Screen
- **Android (Chrome):** ⋮ menu → Add to Home screen

It gets an icon and opens full-screen without browser chrome.

---

## Distribution

Print a QR code pointing at the URL and post it in the shop. Any QR generator works — search "QR code generator," paste the Pages URL, download the image.

---

## Before anyone uses this

The tool carries an OPSEC notice that users must acknowledge before it will generate anything:

> No classified, NNPI, or CUI content. No plant parameters, no design data, no casualty response procedures, no operational schedules. Counts and outcomes only. Finished narratives get hand-typed into NAVFIT98A on the government machine.

The generated prompt repeats this instruction to the AI. It is not a substitute for supervision — read what your people are putting in.

---

## What the tool does not do

Ranking, summary group standing, and the EP/MP/P promotion recommendation are set by the chain of command. They are deliberately absent from the worksheet, and the generated prompt explicitly forbids the AI from writing a ranking statement or assigning a promotion tier.

The Chief Petty Officer closing statement is the one recommendation the tool will produce, and only when the member is marked EWS-qualified and the wording is selected by hand.

---

## Updating it

Edit `index.html` directly on GitHub (open the file → pencil icon → commit) or upload a replacement. Pages redeploys in about a minute. Users get the new version on their next page load — no need to resend the link.
