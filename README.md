# About the project

SAT is a script created for unpack/repack image files (especially Generic System Images). The aim of SAT is to make some steps simple and automatically. It also contains some features related to GSIs:

  - reduce size of system image file
  - convert system from AB architecture to A-only

# Requirements

In order to use SAT, you have to install some additional packages:
- simg2img
- img2simg

#### On Ubuntu: 
```sh
$ sudo apt-get install simg2img img2simg
```

# Installation
To install SAT just clone this repo:
```sh
$ git clone https://github.com/SoulHunter24/android-tool.git
```
#### or 
download and unpack archive from [releases]

# Usage
SAT has basiclly 4 modes (auto, unpack, repack, no-mode). In each mode you can use some addiotional options (possible to use few options in one command).
Generally, in order to run a script type:
```sh
$ ./sat.sh <OPTIONS>
```
See a full documentation [here]

# Update
To update SAT run below command:
```sh
$ ./sat.sh --update
```
It will do everything automatically and keeps your settings in "default.conf" file.


   [releases]: <https://github.com/SoulHunter24/android-tool/releases>
   [here]: <https://github.com/SoulHunter24/android-tool/blob/testing/documentation.md>
   
