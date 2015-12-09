# youtube-album-uploader

A node CLI to upload an mp3 album to youtube. 

`youtube-album-uploader "/path/to/music/folder"`

## Getting Started

Requires [ffmpeg](https://www.ffmpeg.org/) be installed. On windows, make sure to add the following PATHs (with actual paths to whereever you installed ffmpeg):

    FFPROBE_PATH - C:\ffmpeg\bin\ffprobe.exe
    FFMPEG_PATH - C:\ffmpeg\bin\ffmpeg.exe



You can install youtube-album-uploader using npm:

    npm install -g youtube-album-uploader
    
    
    
## Usage 

Just pass the path to the directory containing your music. 

    youtube-album-uploader "path/to/album/folder"

on windows, maybe something like:

    youtube-album-uploader "C:\Documents and Settings\user\My Documents\My Music\music\The Rural Alberta Advantage\Departing"

When it finishes creating the video your browser should open and prompt you to sign in with your Google account and give youtube-album-uploader permission to upload on your behalf.

When everything is done you should get a `Video uploaded successfully!` message. You might have to manually kill the process after that (it's a known issue, sorry).

## Sponsors

Development is sponsored by [Earthling Interactive](https://http://earthlinginteractive.com/).

## Questions

If you have any questions, just [open an issue](https://github.com/jpchip/youtube-album-uploader/issues/new).

## Disclaimer

Please mind the copyrights of whatever it is you end up uploading with this tool. 