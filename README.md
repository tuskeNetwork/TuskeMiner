# Modified XMRig for Tuske

XMRig is a high performance, open source, cross platform RandomX, KawPow, CryptoNight and GhostRider unified CPU/GPU miner and RandomX benchmark. Official binaries are available for Windows, Linux, macOS and FreeBSD.

This is a modified XMRIG for Tuske v1 pow algo.

## Solo Mining

Make sure your local Tuske Daemon is running and synchronization is complete.

xmrig.exe -o 127.0.0.1:20241 -a rx/0 -u "Tuske Mainnet Address" --daemon

(Replace "Tuske Mainnet Address" with your own address)

## Mining backends
- **CPU** (x86/x64/ARMv7/ARMv8)
- **OpenCL** for AMD GPUs.
- **CUDA** for NVIDIA GPUs via external [CUDA plugin](https://github.com/MoneroOcean/xmrig-cuda).

## Build

* **[Build from source](https://xmrig.com/docs/miner/build)**



## Developers
* **[xmrig](https://github.com/xmrig)**
* **[sech1](https://github.com/SChernykh)**


