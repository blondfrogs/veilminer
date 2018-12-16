# VeilMiner

Veil, "Veilminer."

An optimized fork of nevermore developed specially for x16rt.

Based on Christian Buchner's &amp; Christian H.'s CUDA project, no longer active on github since 2014.

Check the [README.txt](README.txt) for the additions


## Donation Addresses

Consider supporting the contributors to this miner by donating to the following addresses:

blondfrogs / blondfrogs#8615 (developer of x16rt miner)

- BTC: 1JXERhRD7KCe1dUEA6AuThYGiwN7h2AR36

- Veil: TBD

- ETH: 0x7327d3a49e1724c64b5969144e7a90150b462b66

brianmct / brian112358 (developer of Nevermore miner)

- BTC: 1FHLroBZaB74QvQW5mBmAxCNVJNXa14mH5

- RVN: RBrianMCTM1xdRF5dMgKC2vB8DdNXn57WP

- ETH: 0x7255ba772ee18bdb8b9af0bdeae2e41f5874fb0b

- DOGE: D7h81HeRVV3xPWL9CqCC2Z6AevG4gBdGxZ

A part of the recent algos were originally written by [blondfrogs](https://github.com/blondfrogs)

This variant was tested and built on Linux (ubuntu server 14.04, 16.04, Fedora 22 to 25)
It is also built for Windows 7 to 10 with VStudio 2013, to stay compatible with Windows 7 and Vista.

Note that the x86 releases are generally faster than x64 ones on Windows, but that tend to change with the recent drivers.

The recommended CUDA Toolkit version was the [6.5.19](http://developer.download.nvidia.com/compute/cuda/6_5/rel/installers/cuda_6.5.19_windows_general_64.exe), but some light algos could be faster with the version 7.5 and 8.0 (like lbry, decred and skein).

About source code dependencies
------------------------------

This project requires some libraries to be built :

- OpenSSL (prebuilt for win)
- Curl (prebuilt for win)
- pthreads (prebuilt for win)

The tree now contains recent prebuilt openssl and curl .lib for both x86 and x64 platforms (windows).

To rebuild them, you need to clone this repository and its submodules :
    git clone https://github.com/peters/curl-for-windows.git compat/curl-for-windows


Compile on Linux
----------------

Please see [INSTALL](https://github.com/tpruvot/ccminer/blob/linux/INSTALL) file or [project Wiki](https://github.com/tpruvot/ccminer/wiki/Compatibility)
