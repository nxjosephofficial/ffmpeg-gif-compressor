# ffmpeg-gif-compressor
This is a shell script that reduces original gif's size with ffmpeg.

script will ask you first for input file name, secondly output file name. If you review script's code you can understand more.

Example: to reduce file.mp4 or file.gif and save output as file-compressed.gif
```
./script.new

file.mp4 (or) file.gif
file-compressed.gif

...
```

### Requirements:
- ffmpeg

ffmpeg for apt:
```
sudo apt install ffmpeg
```
ffmpeg for pacman:
```
sudo pacman -S ffmpeg
```

### How to run:
just give execute permission with that command below:
```
chmod +x /path/to/script.new
```
