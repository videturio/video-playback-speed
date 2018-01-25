# Video Playback Speed

Allows you to change the video playback speed on several sites by clicking a bookmark in your browser.

## Getting Started

These instructions will get you up and running with a bookmark in your browser that you can click to change the video playback speed to any speed you'd like.

Many sites offer only certain playback speeds. On YouTube, you can only choose 0.25, 0.5, 0.75, 1.0, 1.25, 1.5 and 2. With this script, you can set it to any value, e.g. 1.75 or 3.0.

### Prerequisites

Download and install the [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html) browser.

### Supported Sites

* [YouTube](https://www.youtube.com)
* [Udemy](https://www.udemy.com)

### Installation

Follow these steps to set desired playback speed and add bookmark to your browser.

1. Copy the JavaScript code from the videoPlaybackSpeed.js file in this repository.
2. Paste into a text editor, e.g. Atom, Notepad or Sublime Text.
3. On line 2, set the desired playback speed.
```js
// Example where desired playback speed is 2.5x
var ps = 2.5;
```
4. Copy the entire text.
5. Open Google Chrome.
6. Right-click on the bookmarks bar and click "Add page...".
7. Choose a descriptive name for the bookmark, e.g. "2.5x". Paste the copied code into the URL field under the name field.
8. Save.

### Usage

Simply press the bookmark in your bookmark bar.
