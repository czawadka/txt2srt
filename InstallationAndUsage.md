# Installation #
  * Install Java (at least 1.5)
  * Download txt2srt.jar and store it as eg. c:\tools\txt2srt\txt2srt.jar
  * In 'Send To' folder for given user (eg. C:\Documents and Settings\USER\_NAME\SendTo in Windows XP, C:\Users\USER\_NAME\AppData\Roaming\Microsoft\Windows\SendTo in Windows7) create shortcut with command `java -jar c:\tools\txt2srt\txt2srt.jar` and then name it as 'txt2srt'.

If needed txt2srt is using [MediaInfo CLI](http://sourceforge.net/projects/mediainfo/files/binary/mediainfo/) to detect frame rate. MediaInfo CLI has to be accessible from PATH.

# Usage #
  * Select .txt files with subtitles or directories containing .txt files
  * Right click and from 'Send To' menu choose 'txt2srt'
Now convertion process will start and apropriate .srt files should appear. It will detect (using MediaInfo) frame rate automatically.