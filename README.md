# Website Migrator for Mac

[**Download the latest Mac app**](https://github.com/SamDeHerdt/Website-Migrator-releases/releases/latest)

Collect a public website into editable content documents for a redesign or CMS
migration. Each page has a document with its text and images, alongside the
original images in its own folder. Proven translations stay together.

- Entire websites or a single page
- Word documents, images and optional full-page reference screenshots
- Page inventory, crawl notes, activity log and failed-page retries
- Migration redirect drafts in HubSpot CSV format
- Crawl and ZIP progress, time remaining and total size estimates
- In-app update checking under Help

**Requires Apple Silicon (M1 or newer) and macOS 14 or newer.**
Node and Chromium are included; no Terminal setup is needed.

## Install

Download the DMG from Releases. Open it and drag **Website Migrator** into
**Applications**, then open the app. A ZIP containing the same app is also
available. Both assets have checksums in `SHA256SUMS.txt`.

This app is ad-hoc signed, **not Apple notarized**. On first launch, macOS may
require **System Settings → Privacy & Security → Open Anyway**. Approve only the
app downloaded from this repository. Keep Gatekeeper enabled.

## Updates

Open **Help → Check for updates** or the app menu's **Check for updates**.
The app downloads the new version, verifies its checksum, version and bundle
signature, installs after quitting, and reopens. Finish a current export first.
Your exported documents and settings are retained. Manual DMG installation works
as an alternative.

The source repository is private; this repository hosts installers and release
notes only, following the same arrangement as Hubman. Report issues here without
including private website data, exports or credentials.

Content quality depends on the original website. Review representative documents
and crawl notes before treating a migration package as complete. A redirect draft
needs destination review before being imported into a CMS.
