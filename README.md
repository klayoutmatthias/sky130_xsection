
# KLayout XSection script for Skywater 130 process

This script is provided "as is". It is based on the rough process
description given in the Skywater PDK.

This work is preliminary. Here is a list of open topics:

* It is not clear what isolation scheme this technology uses.
  The process description indicates FOX, but the design rules
  and the device cross sections suggest STI. I picked STI
* Many dimensions are guesswork.
* Implants are not fully implemented as their properties are
  unknown (e.g. Vth adjustment implants). 
* Silicide is not indicated and so is silicide blocking
  for resistors.

## Usage

* Install the XSection Package in KLayout ("Tools/Manage Packages")
* Load a layout
* Draw a ruler where you want to create the cross section
* Choose "Tools/Run XSection script" and select the "sky_130.xs" file
  from this repository.
* Next time the script will appear in the recently used file list
  of the XSection menu

## Links

* XSection project: [https://github.com/klayoutmatthias/xsection]
* Skywater 130 PDK: [https://github.com/google/skywater-pdk]
* KLayout PCells for Skywater 130: [https://github.com/mabrains/sky130_klayout_pdk]



