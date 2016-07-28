[![Bare Conductive](http://bareconductive.com/assets/images/LOGO_256x106.png)](http://www.bareconductive.com/)

# Bare Conductive Max/MSP patch for the Touch Board

One-way communication from the [Bare Conductive Touch Board](http://www.bareconductive.com/shop/touch-board/) or [Bare Conductive Pi Cap](http://www.bareconductive.com/shop/pi-cap/) to Max/MSP. All data types are delivered to the patch via USB serial communication (for the [Touch Board](http://www.bareconductive.com/shop/touch-board/)) or OSC (for the [Pi Cap](http://www.bareconductive.com/shop/pi-cap/)) for use with touch or proximity sensing.

## Requirements
* [Bare Conductive Touch Board](http://www.bareconductive.com/shop/touch-board/) running [DataStream](https://github.com/BareConductive/mpr121/tree/public/MPR121/Examples/DataStream) or [Bare Conductive Pi Cap](http://www.bareconductive.com/shop/pi-cap/) running [datastream-osc](https://github.com/BareConductive/mpr121/tree/public/picap-datastream-osc-cpp)

* [Max/MSP 7.0 or later.](https://cycling74.com/downloads/)


## Install

1. Download the [.zip](https://github.com/BareConductive/Max-MSP-Touch-Board-communication/archive/public.zip) or clone the repository to your local machine - if downloading the .zip, extract the contents somewhere that suits you.
1. Plug in your Touch Board via USB or run datastream-osc on your Pi Cap, with --host set to the address of the machine running Max/MSP.
1. Open the patch and follow the onscreen instructions.
