# Youtube Video Downloader

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/50171f1e8102425080e04dab65ffe3e5)](https://www.codacy.com/manual/shubhanshu02/Youtube-Downloader?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=shubhanshu02/Youtube-Downloader&amp;utm_campaign=Badge_Grade)

## Introduction
This is a simple program written in *Python 3* to download YouTube videos directly through Python. This program saves the video in <em> .mp4 </em> format in the same directory as that of the program.

## Usage
The program can be run with or without arguments. Both resolution and URL of the video can be passed as arguments. The program can be run in the following ways - 
1.  ` python main.py -resolution url`
2.  ` python main.py url`
3.  ` python main.py`

>   If the resolution is not passed as an argument, the program displays the available resolutions to download.
>   Now with Progress bar added

## Libraries Used
*   sys
*   pytube
*   urllib