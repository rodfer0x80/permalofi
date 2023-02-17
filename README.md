# permalofi
> easy streams on the cli using ffmpeg

## Requirements
````bash
ffmpeg
open port 554
bash
yt-dlp (optional)
````

## Usage
````bash
./.configs - stream url and key newline separated in format "STREAM_KEY xxxx-xxxx-xxxx-xxxx-xxxx"
./media/vod.mkv - streaming video file
./media/thumbnail.jpg - image cover for video
./media/sound.mp3 - sound file for video
./scripts/stream.sh - mix sound and image to create mkv vod, stream it to youtube
./scripts/clean.sh - past media and vods are archived in ./archive with timestamp
./scripts/sounddl.sh - download sounds from anywhere
````
