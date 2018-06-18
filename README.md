# youtube-dl-bats
These .bat files are just made to simplify the usage of Windows .exe releases of http://rg3.github.io/youtube-dl/ (Source: https://github.com/rg3/youtube-dl) for people who want to just simply use `youtube-dl` as a tool to download high-quality videos from YouTube without using third-party services or software clients (since these usually come with video quality restrictions) rather than use it for development purposes. 

**Note that the  `youtube-dl.exe` file must be stored in the same directory as the .bat files in order to work**

## ytdl.bat
This is the main .bat file used to download videos of YouTube by simply providing the command-line prompt with a YouTube video URL. It will try to download the video in the highest quality possible. Videos with video quality above 720p will have to download the video and audio files seperately and then merge them into one file (thats just how YouTube works for some reason). To merge video and audio files `youtube-dl` requires that FFmpeg (https://www.ffmpeg.org/) is installed on your system.

## ytdlAdvanced.bat
This .bat allows for advanced usage by allowing you to manually enter multiple command-line arguments for `youtube-dl`.

## ytdlFormatList.bat
This .bat lists all of the available video formats that you can download (read more about video format selection usage at https://github.com/rg3/youtube-dl/blob/master/README.md#format-selection).

## ytdlInfo.bat
This .bat lists basic information about your current `youtube-dl` Windows .exe release.

## ytdlQualitySelect.bat
This .bat does the same as `ytdl.bat` but allows you to manually specify desired video quality and video fps.

## ytdlUpdate.bat
This .bat updates your current `youtube-dl` .exe file if an update is available.

## Note
This repository and its files are currently very barebones. I might add extra features later on. Feel free to contribute if you wish!
