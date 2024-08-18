# files

```
ffmpeg -i ~/Downloads/BigBuckBunny.mp4 -ss 00:00:30 -t 03:00:05 -c:v libx264 -crf 23 -preset medium -c:a aac -b:a 128k /Volumes/Mydisk_800/files/01.mp4
ffmpeg -i ~/Downloads/BigBuckBunny.mp4 -ss 00:00:30 -t 03:00:05 -c:v libx264 -b:v 1000k -c:a aac -b:a 128k /Volumes/Mydisk_800/files/02.mp4
```
