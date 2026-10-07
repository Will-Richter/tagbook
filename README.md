# Tagbook Electrical Testing

A phone-friendly electrical testing logbook.

**Open the app:** https://will-richter.github.io/tagbook/

## What it does

- **Test and tag logbook.** Add an appliance, enter the readings, and it works out pass or fail, the tag colour and the retest date. Every appliance keeps its full test history.
- **Test certificates.** Queensland Certificate of Testing and Compliance, Certificate of Testing and Safety, or a plain test report, with circuit results and sign-off. Downloads as a PDF with your logo and signature.
- **RCD log.** Push-button and trip-time tests checked against the limit for the RCD's rating, with both retest dates tracked.
- **Home screen.** What is overdue, due in the next 30 days, failed, or still in draft.
- **Exports.** Site register PDF, logbook CSV, and a full backup file you can restore on another device.

## Where your records are kept

This hosted version saves records in the browser on the device you use. Nothing is sent to a server. Clearing the browser's site data removes them, so download a backup from **More → Your data** regularly and keep it somewhere safe.

On a phone, use **Add to Home Screen** to install it like an app. It keeps working without reception once it has been opened once.

## Before you rely on it

Pass limits and retest intervals are pre-filled with commonly used AS/NZS 3760 and AS/NZS 3012 values. Check them against your own copy of the standards and your state's rules. They can be changed under **More → Limits and numbering**.

Tagbook records what you enter. The person testing is responsible for the readings, the result, and compliance with the standards and licensing rules that apply.

## Files

- `index.html` is the whole app.
- `pdf-lib.min.js` builds the PDFs ([pdf-lib](https://github.com/Hopding/pdf-lib), MIT licence, see `pdf-lib-LICENSE.md`).
- `sw.js`, `manifest.webmanifest` and the icons make it installable and usable offline.

© 2026 Will Richter. All rights reserved.
