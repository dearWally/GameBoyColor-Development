# GameBoyColor-Development

I wrote code for the GameBoyAdvanced years ago. See [Circuit Cellar Magazine, February 2006](http://www.cc-webshop.com/Circuit-Cellar-Issue-187-February-2006-PDF-FI-2006-187.htm). 

Of course I had a nice XPort cartridge to link my computer to the GBA. There was no hardware work
involved -- just C++ and learning the hardware registers on the GBA.

GBC development is nothing new. There are lots of tutorials on GBC hacking (see the links below).
This repo is a journal of my experience and any code I produced along the way. 

I started with a Game Boy Color and several cartridges I bought from ebay. 

![](https://github.com/topherCantrell/GameBoyColor-Development/blob/master/art/IMG_0310.JPG)

The Gameboy Color is backwards compatible with the Gameboy (non color). That means I can start with
simpler programs that don't access the color registers. The cartridge pinouts are the same.

## Links

This is my primary source. Here is how to remove the existing rom and replace with an FRAM. There
is even a circuit here to program it.
[Gameboy Fram Cart](http://www.robotdungeon.com/ElectronicProjectGameboyROM.html)

[Wikipedia](https://en.wikipedia.org/wiki/Game_Boy_Color)

## Development Cartridges

![](https://github.com/topherCantrell/GameBoyColor-Development/blob/master/art/IMG_0322.JPG)

Two of the cartridges (Tarzan and Winnie the Pooh) had clear cases. I chose to hack those.
The screws holding the cartridges together have the Nintendo star-pattern heads. I was able
to carefully unscrew them with needle-nose pliars.

![](https://github.com/topherCantrell/GameBoyColor-Development/blob/master/art/IMG_0322.JPG)

The Tarzan cartridge is very simple: just the ROM and the memory mapper chip. The Pooh cartridge
has a battery-backed RAM in it.

The cartridge is one-sided. It slides into the back of the unit so that the connector pads
and parts are facing out (not in towards the unit).

![](https://github.com/topherCantrell/GameBoyColor-Development/blob/master/art/cartPinout.png)