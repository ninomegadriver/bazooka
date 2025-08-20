# Bazooka, Taito do Brasil, 1977<br/>AdvanceMAME Emulator Driver And ROMs
  
  This repository folder contains an AdvanceMAME driver implementation for the Bazooka arcade game. Read the driver's [source code](https://github.com/ninomegadriver/bazooka/tree/main/advancemame-bazooka/src) for an extended documentation of the game. The original game logic TTL have been simulated, graphics and audio have been also implemented making the game fully playable. When the game starts, you'll see a small "bazooka" at the bottom of the screen simulating the position of the real hardware weapon.  
  
*IMPORTANT*: Check [COPYING](https://github.com/ninomegadriver/bazooka/blob/main/advancemame-bazooka/COPYING) for the license of all the sources and files provided within this folder repository.
  
![Bazooka Running on AdvanceMAME 5.0](https://raw.githubusercontent.com/ninomegadriver/bazooka/refs/heads/main/advancemame-bazooka/screenshot.png)  
  
## How to apply the patch and play  
  
  - Download [AdvanceMAME 5.0](https://github.com/amadvance/advancemame/releases/download/v5.0/advancemame-5.0.tar.gz) from the releases on the official repository and extract it, example:
```
    wget -O - https://github.com/amadvance/advancemame/releases/download/v5.0/advancemame-5.0.tar.gz | && tar zxvp
```
  - Download the [patch file](https://raw.githubusercontent.com/ninomegadriver/bazooka/refs/heads/main/advancemame-bazooka/advancemame-5.0_bazooka.patch):
```
    wget "https://raw.githubusercontent.com/ninomegadriver/bazooka/refs/heads/main/advancemame-bazooka/advancemame-5.0_bazooka.patch"
```
  - Apply the [patch file](https://raw.githubusercontent.com/ninomegadriver/bazooka/refs/heads/main/advancemame-bazooka/advancemame-5.0_bazooka.patch) like:
```
    cd advancemame-5.0
    patch -p1 < ../advancemame-5.0_bazooka.patch
```
   - Build AdvanceMAME the way you like and install it, example:
```
   ./configure && make -j8 && sudo make install
```
   - Download the provided [bazooka.zip](https://github.com/ninomegadriver/bazooka/blob/main/advancemame-bazooka/rom/bazooka.zip) ROM set and place it into your "rom" folder. Example on a linux:
```
   mkdir -p ~/.advance/rom
   cd ~/.advance/rom
   wget https://github.com/ninomegadriver/bazooka/blob/main/advancemame-bazooka/rom/bazooka.zip
```
   - Run it like any other game, ex:
```
   advmame bazooka
```
