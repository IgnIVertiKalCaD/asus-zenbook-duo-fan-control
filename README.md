# asus-CPU-fan-control

This bash script allows you to switch between Turbo and auto cooling modes on your CPU fan.

*Note: This script does not support GPU fans, as their speed is software-locked and should be controlled through the respective GPU drivers.*

![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

____
Who doesn't know, since linux 6.6 (I don't remember), asus-wmi is built into the kernel, but zenbook support came later. Check 
```
/sys/class/leds/asus::screenpad/

```
____
## Currently tested with

|  ZenBook Duo |
|:--------:|
| UX482 (BIOS ver 318)   |
| UX582HM (BIOS ver 303) |

____

## Installation

```
git clone https://github.com/IgnIVertiKalCaD/asus-zenbook-duo-fan-control 

```
____

## Usage

```
sudo chmod +x asusfancontrol.sh
sudo sh asusfancontrol.sh

```

____
