<p align="center">
  <a href="https://github.com/crystalux-project">
    <img src="https://raw.githubusercontent.com/crystalux-project/branding/main/crystalux-logo-minimal-iso.png" alt="Logo" width="150" height="150">
  </a>
</p>
<p align="center"> 
<h2 align="center"> Crystal ISO </h2>
</p>
<p align="center">
<img src=https://img.shields.io/github/stars/crystalux-project/iso?style=flat&color=a900ff />
<img src=https://img.shields.io/github/forks/crystalux-project/iso?style=flat&color=a900ff />
<img src=https://img.shields.io/github/issues/crystalux-project/iso?style=flat&color=a900ff />
<img src=https://img.shields.io/github/issues-pr/crystalux-project/iso?style=flat&color=a900ff />
<a href="https://discord.gg/yp4xpZeAgW"><img alt="Discord" src="https://img.shields.io/discord/825473796227858482?color=blue&label=Discord&logo=Discord&logoColor=white"?link=https://discord.gg/yp4xpZeAgW&link=https://discord.gg/yp4xpZeAgW> </p></a>
<p align="center"> Build or download the Arch-based CrystalUX iso. </p>

## Dependencies:
* `pacman-contrib`
* `archiso`
* `github-cli`

## How to Build:
You will have to use Arch or Arch-Based distros to build this ISO File.
* Install Dependencies
* Go to the project folder
* Run `./build_iso.sh`
    * If you get an error about `/tmp/<something>` running out of space, reboot (to clear tmpfs), then re-run with a dir to use as temp (e.g. `./build_iso.sh FOOBAR`)