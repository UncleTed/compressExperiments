# Compression Experiments

Run the files through the following compression programs, recording the orignal sizes and the compressed sizes on the google spreadsheet.
- zip
- compress
- gzip
- bzip2

The google spreadsheet is located at: ___ (but you have to be invited)


## How to make image files
Use the convert program which is part of ImageMagic
- Create a png file where all the pixels are red:
`convert -size 1000x1000 xc:#990000 red.png`
- Or a jpeg:
`convert -size 1000x1000 xc:#990000 red.jpeg`

- Random pixel image files: `convert -size 1000x1000 xc: +noise Random random.png`


### Bibliography
- https://im.snibgo.com/noise.htm
- https://brunogirin.blogspot.com/2009/09/making-noise-with-imagemagick.html
