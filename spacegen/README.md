# ShiKage's Space Generation
This is a set of code, designed for RhostMUSH, to be used in the automatic
generation of star systems. This is being built to work with the 
HSpace space system. It will expect a single star system to each
HSpace universe.

The star system generation is built off the Traveller 5 rules while using
the classic Elite algoritm as a basis for the system naming process. The
reason for this is to be able to later expand this with some additional
traveller based coded systems to support things such as travel, trade,
etc.

## Installation
The code is quite simple to install but it will require Mushcode Pretty
Printer (MPP) or a similar Mushcode formatter. MPP can be obtained from
the [here](http://download.pennmush.org/Accessories/).

I, myself, use Tinyfugue and MPP to install the code. This can be with 
the following command:
/quote !mpp < spacegen.mpp

## Updating
Updating the code is handled automatically by the install script, 
**provided you did not change any of the object names**. The script
searches for the objects by their expected names.

## Contents
This code package includes the following:
* Core: This is the core and parent object, it contains references
  to other objects and some shared code.
* RNG: RNG or Random Number Generator functions for use by other
  commands and functions.
* NameGen: This implements the classic Elite planet/system naming
  algorithm.


