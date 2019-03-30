# v4l2cam
Publicly available C file to read a V4L2 camera into PPM files.

## Compile
You may need to install headers.
```bash
sudo apt install cmake libv4l-dev/stable
```

```bash
mkdir build; cd build; cmake ..; make
./v4l2cam
ls # look for the files named as out000.ppm
```
