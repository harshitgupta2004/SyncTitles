# SyncTitles

A Python program to automatically sync subtitles with the wrong framerate by comparing speech in the video to text in the subtitles. 

This program is usefule for those whose subtitles keep getting out of sync with audio/video.

The tool offers two methods of synchronization: manual and automatic. In the manual mode, users can input specific timestamps from the SRT file and the corresponding video. The program then calculates correction factors based on these timestamps and applies them to the entire subtitle file, aligning the subtitles with the video.

## Execution
Simply download and execute **subtitle_sync.py** file to get the program running.
- Select SRT file and the video you want to sync it to
- Choose settings (encoding, auto sync options)
- Press Auto and wait until complete

Just click the close window to quit the process.

If you get an encoding error, try another encoding from the dropdown and press OK.
You can also edit the generated times manually and press OK to resync.

## Installation
The app's installation process is quite easy. Simply clone this github repo from your terminal or press download as zip, and then unzip the downloaded folder to the directory of your choice.

Then navigate to the the directory and inside the folder open your terminal and type:
```
pip install -r requirements.txt
```
