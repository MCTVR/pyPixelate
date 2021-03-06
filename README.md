# pyPixelate
 pyPixelate pixelates your image into a pixel art asthetic.

## Example:
### Original & Output (pyPixelate.py, Original, 25px per tile, 50px per tile, 100px per tile)
<p float="left">
<img src="target.jpg" height="300px" /><img src="output.jpg" height="300px" /><img src="output1.jpg" height="300px" /><img src="output2.jpg" height="300px" />
</p>

### Original & Output (pyPixelateE.py, Original, 25px per tile, 50px per tile, 100px per tile)
<p float="left">
<img src="target.jpg" height="300px" /><img src="outputE.jpg" height="300px" /><img src="outputE1.jpg" height="300px" /><img src="outputE2.jpg" height="300px" />
</p>

Credits: <a href="https://akebi-chan.jp/">https://akebi-chan.jp/</a>

## Prerequisites

- numpy
- cv2

## Usage (pyPixelate.py)

Windows:
```console
python pyPixelate.py <image> <block size> <output image (e.g. 1.jpg)>
```

Linux & macOS:
```console
python3 pyPixelate.py <image> <block size> <output image (e.g. 1.jpg)>
```

## Usage (pyPixelateE.py) (E for Enhanced and Experimental)
Windows:
```console
python pyPixelateE.py <image> <block size> <output image (e.g. 1.jpg)>
```

Linux & macOS:
```console
python3 pyPixelateE.py <image> <block size> <output image (e.g. 1.jpg)>
```

It might take a while to create a the pixelised picture.

## Parameters
- `PADDING` (Image Output Size, must be a multiple of `block size`)
- `GRID_LINES` (To produce grid lines in final output, boolean value)


