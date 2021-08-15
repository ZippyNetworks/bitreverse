# BITREVERSE - REVERSE MINING - My attempt to modify original project to work with AMD Stream vs CUDA using HIP
Bitcoin, Altcoins and Ethereum address collision mining software.
Multi GPUs, full CUDA optimised.

The unique feature about this software is that each generated private key is tested against millions of Bitcoin, Altcoin or Ethereum addresses. Performances are 48'000'000* keys against 18'000'000* addresses (compressed/uncompressed and Ethereum) making 864'000'000'000'000 matching per second with a small GTX 1060 3GB. Mining Rigs are Welcome!



## Build dependencies

Windows:
  - Visual Studio 2015
  - CUDA 9.2 Toolkit
  - Boost

Linux:
  - nvcc (CUDA 9.2) see env.sh and compile.sh
  - CUDA 9.2 Toolkit
  - Boost

## REST server

A REST Json server is used to communicate with the GUI (node.js & Electron) The default port is 5132 but it can be changed as the first argument of the command line.

The commands are:
			/found
			/device
			/status
			/user
      /version

## Supporting this project

If you find this project useful and would like to support it, consider making a donation. Your support is greatly appreciated!

**BTC**: `1KiAsmCB37Kn6LqQhfriaZsmFDiL9FGYXZ`
