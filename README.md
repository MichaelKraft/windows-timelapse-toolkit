# Windows TimeLapse Toolkit
Windows toolkit for taking periodic screenshots and generate a time lapse video from them.

### How to Use

- Download the latest release from https://github.com/felladrin/windows-timelapse-toolkit/releases
- Unzip the folder wherever you want. Screenshots and timelapse videos will be saved inside that folder.
- Double-click '*start-taking-screenshots*'. Then press Ctrl+C when you want to finish taking screenshots.
- Double-click '*create-timelapse-video*'. The more screenshots you have, the longer it'll take to create it.
- Optionally edit the '*config*' file to suit your needs. The default configuration is:
  - Take a screenshot every 30 seconds.
  - Create the timelapse videos displaying 10 screenshots per second.
  - Use [FFmpeg 'veryslow' preset](https://trac.ffmpeg.org/wiki/Encode/H.264#a2.Chooseapreset) to create videos with the smallest possible size.
- That's it! You'll find your timelapses inside the '*videos*' folder.

### Third-party softwares used

- [FFmpeg](https://github.com/FFmpeg/FFmpeg) (LGPL-licensed with optional components licensed under GPL)
- [screenshot-cmd](https://code.google.com/archive/p/screenshot-cmd/) (New BSD License)