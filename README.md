# Video Screenshot

This application allows users tocconvert a video into images by capturing screenshots from a video file.

## How to install
Install one of the html page and open them in your browser. You are ready to go!

## Features

- Choose a video file and output format (PNG/JPEG)
- Adjust screenshot frequency and playback speed (there's no point it choosing a lower playback speed AFAIK)
- Option to play audio and show preview
- Fast mode for quicker screenshot capture

## How to Use

1. Select a video file using the "Choose File" button.
2. Adjust settings such as screenshot frequency, output format, playback speed, etc.
3. Click the "Start Screenshot" button to begin capturing screenshots.
4. Optionally, you can enable fast mode for quicker screenshot capture.
5. Once capturing is complete, you can download the screenshots individually or as a zip file.

## Changelog

| Old name         | Changelog / Notes                                                                                             | What version it is based on | New name                   |
|------------------|----------------------------------------------------------------------------------------------------------------|-----------------------------|----------------------------|
| v1-works         | First version, works by right clicking images and selecting "Saving image as"                                  | None                        | v1-works                   |
| v2-fasterprocessmaybe | Restored from .bak file, doesn't change anything useful                                                        | v1                          | v2 (trashcan)              |
| v2a-playbackspdchg | Is definitely broken, 1st added playback speed                                                                 | v2                           | v2.1 (trashcan)            |
| v2b-download     | Added download all and download by packs of 10, the 10 pack download is useless                                | v2                           | v3                          |
| v2c-generalQOLupg | General quality of life upgrade, added ETA, % and mute option, how it works is super legacy: video plays and there are screenshots | v3                      | v3.1                        |
| v2d-betterv2c    | Added show preview option                                                                                      | v3.1                        | v3.2                        |
| v2e-backendrework| Added playback speed and fast mode (fast mode just doubles playback speed) there is no download button :/      | v3.2                        | v4-fastmodebutmissingdownloads (trashcan) |
| v4.1-fastmode   | Basically v4 but with a div added so we can download it NVM too much work so abandoned                         | v4 | v4.1-fastmode (trashcan)   |
| v2f-inal         | Thought it was the final one but there were tons of small fixes, plus it's not the original v2f, since CSS styles were added | v4.1  | v5-Styles                  |
| v2f.1-test       | Test but I don't remember of what                                                                             | v5                  | v5.1-experimental (trashcan) |
| v2f.2-smallchange | It reorganises the variables (backend), and the packets count are now fixed (previously, it just added 10, now it's fixed by adding 10, but when it comes to the end it stops) but the 10pack are just blank zip files and the video plays automatically so it's deleted | v5.1   | v5.2-10packcountfix (trashcan) |
| v2g-slider       | Added a slider for changing fastiness but is completely broken                                                 | v5.2 | v6-slider (trashcan)       |
| v2h-onlydldall   | Removed 10 pack download since they don't work anymore                                                          | v7          | v7-removedDowload          |
| v2h.1-TOOfastFASTmode | Browser limit playback speed but it is indeed too fast and only captures one frame removed playback speed option | v7        | v7.1-SuperFastMode (trashcan) |
| v2h.2-fixedv2h.1 | Fixed the previous version by adding some dark magic script (that doesn't work yet) BTW the UI says mute but the JS logic wasn't implemented yet, added reverse too | v7.1 | v7.2-importantUpdate (trashcan) |
| v2h.3-WORKSsuperWELL | Took v7.2 promises and made them real, added help section at the end                                           | v7.2 | v8-stableRelease           |
| v2h.3.1-addingQUALITY | Added quality factor but doesn't work                                                                         | v8           | v8.1-qualityFactor (trashcan) |
| v2h.1b-defaults | Fresh start, alternative branch of v2h. There were too many bugs. Basically the same as v2h but with changed default parameters | v7         | v9-Works                    |
| v2h.1b.1-infotxt | Adds an info.txt file to the zip folder. Will probably be the last one...                                      | v9                | v9.1-info                   |


## Help (as of v9.1)

- **Start Screenshot**: Click this button to start capturing screenshots from the video.
- **Select Video File**: Choose a video file that you want to extract screenshots from.
- **Screenshot Frequency**: Set the time interval (in seconds) between each screenshot. Higher values mean fewer screenshots.
- **Output Format**: Select the desired format for the output screenshots (JPEG or PNG).
- **Play Audio**: Toggle this option if you want to include audio from the video.
- **Show Preview**: Enable this option to view a preview of each screenshot as it is captured.
- **Fast Mode**: Enable fast mode to capture screenshots at a faster rate, useful for quickly extracting screenshots.
- **Reverse Mode**: Enable to download images in reverse order. (Ex: Last frame will be named screenshot_1.jpeg, etc.)
- **Info.txt**: Enable to join a info.txt in the zip folder.

For more detailed instructions, please refer to the application interface.

## Authors

- [xpeuvr327](https://github.com/xpeuvr327)
- ChatGPT
