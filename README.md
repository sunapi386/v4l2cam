# v4l2cam
Publicly available C file to read a V4L2 camera into PPM files.

## Compile

On a fresh system, you may need these
```bash
apt install -y cmake make gcc g++ gdb git tree
apt install -y libv4l-dev/stable
```

You may need to install headers.

```bash
mkdir build; cd build; cmake ..; make
./v4l2cam
ls # look for the files named as out000.ppm
```
