---
layout: default
title: "Rain Tracker - Support"
permalink: /rain-tracker-app/support
---

**Support**

Rain Tracker lets you log rain measurements, which are stored in your own private iCloud account via Apple's CloudKit.
There are no accounts to create and no data is sent to the developer.

**Frequently Asked Questions**

*Why don't I see my measurements on another device?*

Make sure you're signed into the same iCloud account on all your devices, and that iCloud Drive is enabled in your device's Settings.
Syncing can also take a few minutes for large numbers of measurements.

*Can I get my data back if I delete the app?*

Yes.
Your measurements are stored in iCloud, not on the device, so reinstalling the app and signing into the same iCloud account will restore your data.

*How do I delete my data?*

You can delete individual entries within the app.
To remove all Rain Tracker data from iCloud, in the Rain Tracker app on your device open *Settings → Delete All Data* in the *Data Management* section.
This will sync with iCloud to delete the measurements there too.

*How do I export my data?*

In the Rain Tracker app on your device, open *Settings → Export Data* in the *Data Management* section.
Rain Tracker builds a CSV file (`rain_data.csv`) with every record you've logged and opens the share sheet so you can save it, AirDrop it, email it, or send it anywhere else iOS can share a file.

> Exported amounts are always in inches, regardless of your unit setting.

*How do I import data?*

In the Rain Tracker app on your device, open *Settings → Import Data* in the *Data Management* section and pick a CSV file.
If you already have records, you'll be asked to **Merge** (add the new rows alongside what you have) or **Replace All** (delete existing records first, then import).

> Merge doesn't check for duplicates — importing the same file twice will double up those entries.

*What format does an import CSV need to be in?*

Three columns, in order: `date` (`yyyy-MM-dd`, required), `amount` (a plain decimal number in inches, required), and `time_of_day` (`Unknown`, `Night`, `Morning`, `Afternoon`, or `Evening`, optional — blank or incorrect values become `Unknown`).

A header row is optional; Rain Tracker recognizes and skips one if present.
Invalid rows are skipped rather than stopping the import, and you'll see a summary of how many rows were imported vs. skipped.

> To easily see the file's format, log at least one measurement in the app and export it first to generate a sample file you can examine.

**Contact Us**

If you have an idea for a feature, run into a bug, or have a question that isn't answered here, email [support.nh.dev@proton.me](mailto:support.nh.dev@proton.me).

For information on how your data is handled, see the [Privacy Policy](/rain-tracker-app/privacy-policy).
