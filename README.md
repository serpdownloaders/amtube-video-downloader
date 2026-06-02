# Amtube Downloader (Browser Extension)

> Download AM Tube videos from adver-media.com. Detect page and host media, use the player button, and save exposed streams.

A browser extension candidate for AM Tube-branded pages that run on adver-media.com. Open a supported video page, start playback if needed, then use the in-page player button or extension controls to capture exposed media candidates. The extension works across a broad network of external media hosts, making it suitable for the complex media routing that AM Tube pages often use.

- Detect media from video tags and metadata on AM Tube-branded pages
- Use an in-page player button instead of hunting through source code
- Works across a wide range of external media hosts
- Save exposed streams directly through your browser
- Includes 3 free downloads to test the workflow first

## Links

- :rocket: Get it here: [Amtube Downloader](https://serp.ly/amtube-downloader)
- :new: Latest release: [GitHub Releases](https://github.com/serpapps/amtube-downloader/releases/latest)
- :question: Help center: [SERP Help](https://help.serp.co/en/)
- :beetle: Report bugs: [GitHub Issues](https://github.com/serpapps/amtube-downloader/issues)
- :bulb: Request features: [Feature Requests](https://github.com/serpapps/amtube-downloader/issues)

## Preview

![Amtube Downloader workflow preview](https://raw.githubusercontent.com/devinschumacher/uploads/refs/heads/main/images/source-repo-readmes/amtube-downloader/assets/workflow-preview.png)

## Table of Contents

- [Why Amtube Downloader](#why-amtube-downloader)
- [Features](#features)
- [How It Works](#how-it-works)
- [Step-by-Step Tutorial: How to Download Videos from Amtube](#step-by-step-tutorial-how-to-download-videos-from-amtube)
- [Supported Formats](#supported-formats)
- [Who It's For](#who-its-for)
- [Common Use Cases](#common-use-cases)
- [Troubleshooting](#troubleshooting)
- [Trial & Access](#trial--access)
- [Installation Instructions](#installation-instructions)
- [FAQ](#faq)
- [Notes](#notes)
- [License](#license)
- [About Amtube](#about-amtube)

## Why Amtube Downloader

AM Tube-branded video pages on adver-media.com often route playback through multiple external media hosts, making it difficult to save videos directly. The standard browser save options rarely expose the final media URL, and generic downloader tools can miss metadata-backed streams entirely.

This extension is built for exactly that kind of messy browser-side media hunt. Instead of requiring you to manually track down source URLs across a chain of third-party hosts, it detects exposed media candidates right from the page you are viewing. The player button attaches directly to the video container, so you do not need to dig through code or switch between tabs to find what you want to save.

## Features

- AM Tube-focused detection on adver-media.com video pages
- In-page player button attached to the video container
- Detection from direct video tags and metadata-backed stream references
- Broad external-host permission coverage for complex media routing
- Offscreen download handling with AM Tube folder defaults
- Context menu support for quick access to download options
- Desktop notifications for download status updates
- Works across HTTP and HTTPS page variants
- Transparent candidate status with clear readiness information
- 3 free downloads included for testing

## How It Works

1. Install the extension from the latest release.
2. Open Amtube and go to a supported video page.
3. Start playback so the extension can detect the media.
4. Open the popup or use the on-page controls.
5. Choose the quality option you want.
6. Start the download and wait for the MP4 export to finish.
7. Save the final file locally.

## Step-by-Step Tutorial: How to Download Videos from Amtube

1. Open your browser and install the Amtube Downloader extension from the latest GitHub release.
2. Navigate to an AM Tube-branded video page on adver-media.com.
3. Wait for the page to load completely, including any embedded media players.
4. Press the play button on the video if media is not detected immediately.
5. Look for the Amtube player button attached to the video container.
6. Click the button or open the extension popup to see detected media candidates.
7. Select the quality option you want from the available choices.
8. Click download and save the MP4 file to your preferred location.

## Supported Formats

- Input: Video streams exposed through page video tags, metadata references, or approved external media hosts on adver-media.com
- Output: MP4

Saved files use MP4 so they are easier to replay on standard media players, move between devices, or archive locally.

## Who It's For

- Users who want to save AM Tube videos from adver-media.com
- Anyone who prefers page-level controls over manual source hunting
- Users who encounter complex media routing across multiple hosts
- People who want a browser-based workflow instead of generic downloader sites

## Common Use Cases

- Save a video from an AM Tube-branded page on adver-media.com
- Detect media surfaced through the page player or page metadata
- Use an in-player button instead of digging through source code
- Work through messy host handoffs without leaving the browser
- Evaluate a target-verified candidate while keeping release-readiness expectations cautious

## Troubleshooting

**No media detected after opening a page**
Start video playback first. Some pages only expose media streams after the player begins buffering.

**The player button does not appear**
Make sure you are on a supported adver-media.com page. The button attaches to the video container, so the page must load fully.

**Download fails or produces a broken file**
Try a different quality option if available. Some external hosts may serve streams that require a specific referer or origin header.

**The extension does not work on some pages**
Not all pages on adver-media.com may expose media through the supported detection methods. Try refreshing the page and starting playback again.

**Getting probe-rejected or low-confidence messages**
This extension is still a candidate and may not work reliably on all pages. Real extraction review is pending, so treat results as experimental.

## Trial & Access

- Includes **3 free downloads** so you can test the workflow first
- Email sign-in uses secure one-time password verification
- No credit card required for the trial
- Unlimited downloads are available with a paid license

Start here: [https://serp.ly/amtube-downloader](https://serp.ly/amtube-downloader)

## Installation Instructions

1. Open the latest release page: [GitHub Releases](https://github.com/serpapps/amtube-downloader/releases/latest)
2. Download the correct build for your browser.
3. Install the extension.
4. Open a supported Amtube page.
5. Use the popup to detect and download the media.

## FAQ

**Why is this called Amtube if the page URL is on adver-media.com?**
The AM Tube brand is presented through adver-media.com runtime URLs. This pairing is part of the extension's candidate profile and may change as the platform evolves.

**Which pages are directly matched?**
The extension matches adver-media.com and www.adver-media.com over both HTTP and HTTPS.

**Which extra hosts are in scope?**
The permission mesh includes a broad range of external media hosts that AM Tube pages commonly use for video delivery.

**What does the extension look for?**
It checks direct video tags, Open Graph video metadata, and Twitter player stream references on supported pages.

**Is this release-ready?**
No. The extension is still a candidate with probe-rejected status and uses generated detection stubs that need real extraction review before a stable release can be claimed.

**Is it released anywhere?**
The extension is available through GitHub Releases but has not been published to official browser stores yet.

## Notes

- Only download content you own or have explicit permission to save
- An internet connection is required for downloads
- The AM Tube brand is presented through adver-media.com runtime URLs, not an amtube.com domain
- This extension is still a candidate and may not work reliably on all pages

## License

This repository is distributed under the proprietary SERP Apps license in the [LICENSE](LICENSE) file. Review that file before copying, modifying, or redistributing any part of this project.

## About Amtube

AM Tube is a video platform that hosts adult content on adver-media.com. The Amtube Downloader extension helps users save videos from this platform directly in their browser without needing external tools or manual source tracking.
