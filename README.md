<!--# spectacleOS Kilimanjaro-->

<img src="https://i.ibb.co/gM7WcTH/specs-matterhorn-head.png" alt="spectacleOS Matterhorn">

![Version](https://img.shields.io/badge/version-5.5.2-informational?style=flat-square) ![GitHub](https://img.shields.io/github/license/aarikpokras/spectacleos?style=flat-square) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/aarikpokras/spectacleos?style=flat-square) ![Maintenance](https://img.shields.io/maintenance/yes/2023?style=flat-square)
## Installation
You can get the latest release [here](https://github.com/aarikpokras/spectacleos/releases), or [use git](https://github.com/aarikpokras/spectacleos#macos) to get the zip from GitHub.

Spectacle is available for all UNIX-like operating systems that can support Python.
**It is recommended to grab the latest release from the releases page (Rather than using git), because those will be the most up-to-date. [Learn More](nocurl.md)**

### MacOS
**Recommended for better user experience (And the program won't work without it): rlwrap**

```bash
brew install rlwrap
```

To install Python, run `brew install python3`. I know brew is *really* slow (if you haven't updated it in a while), but unless you know a better way to get Python, it's the only way.

You can use git to download the repo. Depending on your internet speed, it might download painfully slowly. Sorry 'bout that.

```bash
git clone git@github.com:aarikpokras/spectacleos.git && chmod -R 755 spectacleos spectacleos/bin
```
### Linux and Others
```bash
sudo apt-get install rlwrap
```

To install Python, you can use `apt` or your standard package manager.

`sudo apt install python3`, `sudo yay -S python3`, `sudo yum -S python3`, etc.

```bash
git clone git@github.com:aarikpokras/spectacleos.git && chmod -R 755 spectacleos spectacleos/bin
```
## Running

[Detailed instructions](https://github.com/aarikpokras/spectacleos/wiki/Getting-Started)

### ***Please make sure that you are in the spectacleos directory before running any executables.***

If you just downloaded it, run `chmod -R 755 spectacleos` in the folder that contains spectacleOS.

`cd` into the spectacleos directory.

Run `./first-time` and follow the instructions.

You can open menu.html for a graphical menu.

For information on the Migration Assistant, refer to the [wiki](https://github.com/aarikpokras/spectacleos/wiki/Migration-Assistant-(Migrator)).

To run, run `./specs start`. [Syntax](https://github.com/aarikpokras/spectacleos/wiki/Executables-and-Syntax)

<br />
<br />

Made *by* a real person, *for* real people.

<!--
spectacleOS
Copyright (c) 2023, Aarik Pokras
Under the BSD 2-Clause License
License: https://github.com/aarikpokras/spectacleos/blob/master/LICENSE
-->
