# refind-efifetch

`neofetch`-style theme for the ![rEFInd boot manager](https://sourceforge.net/projects/refind/)

![Screenshot](https://i.imgur.com/kQ1ZsoM.png)

## Installation

1. Locate your rEFInd installation on your EFI partition. This is most likely `/boot/EFI/refind` on Linux, the EFI partition on Windows, or `/dev/disk0s1` on MacOS. `mountvol S: /S` will mount the EFI partition to the `S:` drive on Windows, `sudo mkdir /Volumes/EFI && sudo mount -t msdos /Volumes/EFI` will mount the EFI partition on MacOS, and `cd /boot/EFI/refind` will open the EFI directory on Linux.

2. If it hasn't already been created, use the mkdir command to create a directory named `themes` within the `refind` directory.

3. Clone this repository into the `themes` directory.

4. Append `include themes/refind-efifetch/theme.conf` to the `refind.conf` file in the `refind` folder.

## Credits

Icons taken either directly from, or edited from, dylanaraps' fantastic bash script ![neofetch](https://github.com/dylanaraps/neofetch). All color schemes are taken directly from the logos of the operating systems found therein.

Function icons and mok tool icons are simply Unicode symbols.

The font used to create the icons is from tonsky's monospaced font ![Fira Code](https://github.com/tonsky/FiraCode) (Fira Code is my personal favourite font for terminals and text editors)

## Requests and Bug Reports

Missing your favourite OS? Problem with my theme? Post your requests and bug reports into the Issues section of this GitHub repository.

## License


MIT © Evan Nosich
