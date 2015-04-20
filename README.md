# timeline-url
Chrome devtools extension to generate a URL for your timeline - wip

### Usage 

* user records a timeline. wants to share it
* right click. save timeline as.
* uploads it somewhere. dropbox, drive, cl.ly, etc.
* they go to Sources panel where there's another pane under "Evt Listener breakpoints" called "Get Timeline URL" or something
* In an input field they drop in the URL of the hosted file
* It returns gives the big long URL to copy.
* they send it around to their team or report it in a bug or whatever. 
* everyone can take a look and work together to make it better.

### Screenshot
![](http://i.imgur.com/KZ0Wrr2.png)


### Installation

Not published to store yet, so clone the repo, run `npm install` and `grunt debug` and add `app/` in `chrome://extensions/` > "load upacked extension"

### Example URL

chrome-devtools://devtools/bundled/devtools.html?remoteFrontendUrl=chrome-devtools://devtools/remote/serve_rev/@193610/inspector.html&loadTimelineFromURL=https://dl.dropboxusercontent.com/u/39519/temp/colorpicker-color-dragging-TimelineRawData-20150415T010640.json

(only works in canary for now)
