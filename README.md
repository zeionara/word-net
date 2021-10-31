# WordNet-3.0

This repo contains files from the official [WordNet dataset distribution](https://wordnet.princeton.edu/) for linux with an updated `src/stubs.c` script which in the original version contains invalid references to the tcl toolkit.

The dataset compilation process was tested on the `Ubuntu 20.04` OS and consists of the following commands:

```sh
sudo apt-get install tcl-dev tk-dev mesa-common-dev libjpeg-dev libtogl-dev
./configure
make
sudo make install
```

The result is written to the folder `/usr/local/WordNet-3.0`.

