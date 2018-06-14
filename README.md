# Music File Name Script

The script that moves the music file out of album folder and renames it as just a song name.

Just run
```bash
./run path/to/music/album/folder
```

For creating a service in Automator
```bash
cd /absolute/path/to/this/script/folder/
sh ./run -s "$1"
say "Ready!"
```

