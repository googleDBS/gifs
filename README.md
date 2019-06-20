# gifs

## Installing FFmpeg

`ffmpeg -y -i in.mov -vf fps=10,palettegen palette.png`

`ffmpeg -i in.mov -i palette.png -filter_complex "fps=10,paletteuse" out.gif`
