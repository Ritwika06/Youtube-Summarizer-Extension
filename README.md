## Youtube-Summarizer-Extension
A Chrome extension that utilizes YouTube's transcript functionality to provide concise summaries of videos.

## Requirements
- The following python modules must be installed to run the API
  - ```flask```
  - ```youtube-transcript-api```
  - ```transformers```

## Instructions
- Run ```app.py``` to start the summarizer API.
- Load the custom extension into any Chromium browser.
- Go to any YouTube video and click on the extension logo to start summarizing.


## Outputs
- Video summary will be displayed in the extension tab
- A .txt file containing the summary will be downloaded
