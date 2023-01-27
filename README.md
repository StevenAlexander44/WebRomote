# WebRomote
## A Roku remote control made for Chromium desktop browsers
With more device compatibility to come.

# Features
* Most of the features of a regular Roku remote
* Much faster typing on most Roku Channels
* Big, readable buttons

# Usage

### Prerequisites
* You must know the IP Address of your Roku device (Roku Settings > Network > About > IP, Usually in the form of "192.168.X.XXX")
* Your controller device must be on the same network as your Roku device

## Option 1. Download the HTML file (Works offline)
#### One-time setup
a. Open the [Roku remote HTML code](https://raw.githubusercontent.com/StevenAlexander44/WebRomote/main/romote.html)

b. Save the page by pressing `Ctrl + S` and save to your desired folder

#### To use the remote
c. Open the downloaded "romote.html" in your browser

d. Enter the IP Address of your Roku, and Enjoy!

## Option 2. Allow for Mixed Content (Requires internet connection)
#### One-time setup
a. Open "[chrome://settings/content/siteDetails?site=https://stevenalexander44.github.io](chrome://settings/content/siteDetails?site=https://stevenalexander44.github.io)" in your browser

b. Scroll down for "Insecure Content", and change the value from "Block (default)" to "Allow"

#### To use the remote
c. Open the [remote](https://stevenalexander44.github.io/WebRomote/romote.html)

d. Enter the IP Address of your Roku, and Enjoy!

#### Why do I need to allow insecure connections?
Roku (by default) uses HTTP for their [API system](https://developer.roku.com/docs/developer-program/debugging/external-control-api.md), which is okay for most local network connections. By contrast, Github Pages uses the secure HTTP**S** protocol, necessary for the wider internet, and most browsers don't allow for insecure HTTP requests from a HTTP**S** website by default.

# Issues

## Why doesn't this work on my mobile device, or in Firefox?
I need to get better at CSS.
