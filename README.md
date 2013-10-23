# Lisu ibus-kmfl Unicode keyboard for Linux

## How to install `ibus-kmfl` on Ubuntu

You need to install `ibus-kmfl` from SIL first. If you use Ubuntu, [SIL] has instructions on how to add their repository. Note that you have to replace `precise` with your current Ubuntu distribution.

Then, install `ibus-kmfl` with the following command.
	$ sudo apt-get install ibus-kmfl
 
## How to install the keyboard

Keyboard layout is defined in `lisu.kmn`. It has to be copied to `.kmfl` directory in your home. If the directory is not there yet, create it first. Copy `lisu.kmn` and `icons` directory into `.kmfl`.

### Notes on the keyboard layout

* Lisu tone mark `MYA CYA`(ꓺ) is `Shift + .`
* Lisu punctuation comma (꓾) is `Shift + n` or `minus sign`
* Lisu punctuation full stop (꓿) is `Shift + m` or `equal sign`

---

[SIL]: http://packages.sil.org/ "SIL"
