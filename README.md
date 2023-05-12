# Elona+ Custom-GX 2.17

*\~Believe in Jure and hold a determination to mince.\~*

Elona+ Custom-GX is a new variant of Elona+ based on Elona+ Custom-G, updated with the changes in Elona+ up to version 2.17.

It is originally created and maintained by [Ruin0x11](https://github.com/Ruin0x11), on [this repository](https://github.com/Ruin0x11/ElonaPlusCustom-GX).  
This repository is an unofficial continuation of the above repository using Ruin0x11's [borscht/erystia](https://github.com/Ruin0x11/borscht) decompiler.

### **[Download the latest release here.](https://github.com/JianmengYu/ElonaPlusCustom-GX/releases/)**

## Installation

1. Download Elona+ 2.17 from [here](http://wanwanplus.blog.fc2.com/blog-entry-38.html). Extract it to `elonaplus2.17`.
1a. Backup mega.nz link from [here](https://mega.nz/file/xG9kmJTb#Qh9I7A2CsheXOIq2I7JfOiGMCzg_VBukAMCHzXRpsRQ).
2. Extract the contents of Custom-GX's archive to the `elonaplus2.17` folder, overwriting all existing files.
3. Run `elonapluscgx.exe`.

## Building

1. Follow the installation instructions above. Rename the `elonaplus2.17` folder to `2.05-custom-gx` and move it to the `assets/` folder of this repository.
2. Download the HSP3.4 SDK (`hsp34a.zip`) from [here](http://hsp.tv/make/downlist.html) and extract it somewhere.
3. Copy `hsplua.dll` from the `2.05-custom-gx` folder into the HSP3.4 SDK folder. Otherwise, you'll get an error saying it's missing when running the game from the editor.
4. Open `2.05-custom-gx/main.hsp` with `hsed3.exe` from the HSP3.4 SDK folder. Press <kbd>F5</kbd> to compile and run under debug mode.
5. Press <kbd>Ctrl+F9</kbd> to create an executable named `elonapluscgx.exe`. You can then copy it to your Custom-GX install folder.

**Warning**: If you make any changes to the code, *always make sure the file encoding is set to SHIFT_JIS!* Otherwise, you'll get a lot of cryptic compiler errors.

## Thanks

Glyphy, for creating Elona+ Custom-G.

AnnaBannana and BloodyShade, for creating and maintaining Elona+ Custom.

Everyone else who contributed to Elona+ Custom:
 - Hebiko
 - Glyphy
 - Jehmil
 - Anon(s) from /jp/
 - And others.

Ano, for creating and maintaining Elona+.

f1r3fly, Sunstrike, Schmidt, and Elvenspirit, for contributing to Elona's original English translation.

Noa, for creating a neat little game.

And *you*!
