# INSTAGRAM - Instagib mod for ioquake3

## Compilation

For *nix
  1. Change to the directory containing this readme.
  2. Run `make -j$(nproc)`.

For Windows,
  1. Please refer to the excellent instructions here:
     https://ioquake3.org/help/building-ioquake3/

For macOS, building a Universal Binary (macOS 10.5 to 10.8, x86_64, x86, ppc)
  1. Install MacOSX SDK packages from XCode.  For maximum compatibility,
     install MacOSX10.5.sdk and MacOSX10.6.sdk.
  2. Change to the directory containing this README file.
  3. Run `./make-macosx-ub.sh`
  4. Copy the resulting ioquake3.app in /build/release-darwin-universal
     to your /Applications/ioquake3 folder.

For macOS, building a Universal Binary 2 (macOS 10.9+, arm64, x86_64)
  1. Install MacOSX SDK packages from XCode.  Building for arm64 requires
     MacOSX11.sdk or later.
  2. Change to the directory containing this README file.
  3. Run `./make-macosx-ub2.sh`
  4. Copy the resulting ioquake3.app in /build/release-darwin-universal2
     to your /Applications/ioquake3 folder.


## Installation

  1. Copy files from `build/release-<...>/instagram/vm/` to `<server>/instagram/vm/`


## Contributing

Bug reports and feature requests can be submitted by opening a new issue
under this GitHub repository.


## Credits

ioquake3 maintainers

  * James Canete <use.less01@gmail.com>
  * Ludwig Nussel <ludwig.nussel@suse.de>
  * Thilo Schulz <arny@ats.s.bawue.de>
  * Tim Angus <tim@ngus.net>
  * Tony J. White <tjw@tjw.org>
  * Jack Slater <jack@ioquake.org>
  * Zack Middleton <zturtleman@gmail.com>

Significant contributions to ioquake3 from

  * Ryan C. Gordon <icculus@icculus.org>
  * Andreas Kohn <andreas@syndrom23.de>
  * Joerg Dietrich <Dietrich_Joerg@t-online.de>
  * Stuart Dalton <badcdev@gmail.com>
  * Vincent S. Cojot <vincent at cojot dot name>
  * optical <alex@rigbo.se>
  * Aaron Gyes <floam@aaron.gy>


