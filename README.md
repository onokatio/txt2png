# txt2png

This command convert txt file to png.

## Depends

You have to install these package to run txt2png.

- Bash
- FFmpeg
- xxd

### Ubuntu

```
$ sudo apt-get install ffmpeg xxd
```

### ArchLinux

```
$ sudo pacman -S ffmpeg xxd
```

xxd is developing by vim project. and vim package has xxd.

## Usage

```
txt2png <filename> <width> <height>
```

You can get <filename>.png in current directory.

## Example

```
$ git clone https://github.com/onokatio/txt2png
$ cd txt2png
$ chmod +x ./txt2png
$ ./txt2png ~/COJT/hoge/imagedata.txt 640 480
```

