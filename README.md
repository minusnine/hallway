

## Useful commands:

Flip a video's orientation and extract a few seconds from it.

    avconv -i GOPR0002.MP4 -vf vflip,hflip -ss 00:02:15 -t 00:00:10 -c:a copy out.mkv

