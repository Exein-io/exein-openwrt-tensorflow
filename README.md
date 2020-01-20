# Tensorflow Lite + OpenWRT

## Description
Tensorflow Lite packages for OpenWRT.

* Tensorflow Lite version: 2.0.0
* OpenWRT: 18.06.2, 18.06.3, 18.06.5, 18.06.6


## Usage

Add the following line to `feeds.conf`:
```
src-git tensorflow https://github.com/Exein-io/exein-openwrt-tensorflow.git
```

Run
```
./scripts/feeds update tensorflow
./scripts/feeds install -a -p tensorflow
make menuconfig
```

or copy the repo contents in `package` directory and enable in `make menuconfig`.


In-depth instructions are available in the Tensorflow lite page: https://www.tensorflow.org/lite



## License

See [LICENSE](LICENSE) file
