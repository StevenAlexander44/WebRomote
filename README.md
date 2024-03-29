# A Roku remote control made for desktop browsers
With more device compatibility to come.

# Features
* Most of the features of a regular Roku remote
* Much faster typing on most Roku Channels
* Big, readable buttons
* Use your keyboard to control the Roku device, including:
    * "Home" key to go to home screen
    * Escape to go back
    * Arrow keys for movement
    * Enter to select an item
    * CapsLock to toggle pause
    * "/" for an instant replay
    * "?" for information (the star/asterisk button on a Roku remote)
    * PageUp/PageDown and "End" keys to control volume

# How to use

### Prerequisites
* You must know the IP Address of your Roku device (Roku Settings > Network > About > IP, Usually in the form of "192.168.X.XXX")
* Your controller device must be on the same network as your Roku device

## Option 1. Download the HTML file (Works offline)
### Installation
a. Open the [Roku remote HTML code](https://raw.githubusercontent.com/StevenAlexander44/WebRomote/main/romote.html)

b. Save the page by pressing `Ctrl + S` and save to your desired folder

### Usage
c. Open the downloaded "romote.html" in your browser

d. Enter the IP Address of your Roku, and Enjoy!

## Option 2. Allow for Mixed Content (Requires internet connection)
### Installation
a. Open "[chrome://settings/content/siteDetails?site=https://stevenalexander44.github.io](chrome://settings/content/siteDetails?site=https://stevenalexander44.github.io)" in your browser

b. Scroll down for "Insecure Content", and change the value from "Block (default)" to "Allow"

### Usage
c. Open the [remote](https://stevenalexander44.github.io/WebRomote/romote.html)

d. Enter the IP Address of your Roku, and Enjoy!

### Why do I need to allow insecure connections?
Roku (by default) uses HTTP for their [API system](https://developer.roku.com/docs/developer-program/debugging/external-control-api.md), which is okay for most local network connections. By contrast, Github Pages uses the secure HTTP**S** protocol, necessary for the wider internet, and most browsers don't allow for insecure HTTP requests from a HTTP**S** website by default.

# TODO

## Make it work on mobile browsers
In the meantime [Option 1](option-1-download-the-html-file-works-offline) might work, or use an app:
* This project's inspiration: [RoMote](https://github.com/wseemann/RoMote)
* [The official Roku app](https://www.roku.com/mobile-app).

## Make a database system for different Roku devices (IP addresses)
In the meantime, to reset the IP, press the Delete key on your keyboard, or clear cookies for the webpage.

## Make buttons and keyboard shortcuts easily configurable.
Currently one would have to change the source code to be able to do this. One might want to change their layout with drag and drop.
