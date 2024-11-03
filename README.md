# Medium Freedium Redirector

A Chrome extension that automatically redirects Medium articles through Freedium for unrestricted reading.

## Installation

1. Download or clone this repository
2. Open Chrome and go to `chrome://extensions/`
3. Enable "Developer mode" in the top right corner
4. Click "Load unpacked" button
5. Select the directory containing this extension

## Features

- Automatically redirects Medium articles to Freedium
- Works with both subdomain URLs (e.g., `username.medium.com`) and path URLs (e.g., `medium.com/@username`)
- No configuration needed

## How it works

The extension uses Chrome's declarativeNetRequest API to automatically redirect all Medium URLs through Freedium's service.