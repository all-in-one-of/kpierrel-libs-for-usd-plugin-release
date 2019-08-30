
PixarUSD Plugin Libraries on Windows
======

## Installation:

1. Get kpierrel-libs-for-usd-plugin-release:

    * Option 1: Navigate to the folder you want to contain this repository, and from BASH / Git BASH type:
`git clone https://github.com/kpierrel/kpierrel-libs-for-usd-plugin-release.git`
    * Option 2: Download the desired release directly from the [releases page](https://github.com/kpierrel/kpierrel-libs-for-usd-plugin-release) and extract it to the desired location.

1. Create a variable called **USDS** that points to the new folder, then append these enviroment sets to your own houdini.env:

    * `USDS = /path/to/kpierrel-libs-for-usd-plugin-release`
    * `HOUDINI_OTLSCAN_PATH = $USDS/otls;&`
    * `HOUDINI_SCRIPT_PATH = $USDS/scripts;&`
    * `HOUDINI_PATH = $USDS;&`

2. Maybe you need to add the two enviroment sets to your houdini.env:

    * `HOUDINI_OCL_DEVICETYPE = CPU`
    * `HOUDINI_USE_HFS_OCL = 0`

## For more information: [Introduciton to USD.](http://graphics.pixar.com/usd/docs/Introduction-to-USD.html)
