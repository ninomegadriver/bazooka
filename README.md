# Bazooka, Taito do Brasil, 1977<br/>Repair, documentation, emulation and preservation repository
  
![Full Restored Cabinet at Pinball Club SP](https://github.com/ninomegadriver/bazooka/blob/main/images/2ndRestore/full-restored-cabinet.jpg?raw=true)| 
  
This repository is dedicated to the preservation of the "Bazooka" arcade game by "Taito do Brasil", an entire TTL hardware video game system initially released in 1977. It includes my personal repair logs, with hardware blueprints, documentation and a fully playable AdvanceMAME game driver.  
  
## Repository Index
1 - [First Restore Log](https://github.com/ninomegadriver/bazooka/tree/main/images/1stRestore)<br/>
2 - [Second Restore Log](https://github.com/ninomegadriver/bazooka/tree/main/images/2ndRestore)<br/>
3 - [Hardware Blueprints](https://github.com/ninomegadriver/bazooka/tree/main/images/blueprint)<br/>
4 - [Decoded Graphics](https://github.com/ninomegadriver/bazooka/tree/main/images/DecodedGFX)<br/>
5 - [PROM Dumps](https://github.com/ninomegadriver/bazooka/tree/main/dumps)<br/>
---
## 5 - [Fully playable AdvanceMAME game driver](https://github.com/ninomegadriver/bazooka/tree/main/advancemame-bazooka)<br/>
  
With the primary objective of preserving the game's history, I've chosen to convert all my discoveries, reverse engineering, decoding, cracking and hacking into a MAME driver source code. The fork of MAME chosen was the AdvanceMAME, because of its lightweight and vast portability, being able to compile and run smoothly not only on modern computers, but also on simplified framebuffer only systems. It’s an ongoing WIP but the game is now fully playable with all the logic simulated, graphics and audio emulated.  
  
  **[Check the advancemame-bazooka README.md file](https://github.com/ninomegadriver/bazooka/tree/main/advancemame-bazooka) for more information, including on how to patch the emulator, compile and run the game**  
  
![Bazooka Running on AdvanceMAME 5.0](https://raw.githubusercontent.com/ninomegadriver/bazooka/refs/heads/main/advancemame-bazooka/screenshot.png)  
  
**You're very welcome to contribute!**  
  
You can reach me by [email](nino@nino.com.br) or over social media under @ninomegadriver or @ninomegad.  
  
Help needed:  
- If you have any working or non-working version of the hardware, please share so we can compare the findings;  
- If you want to contribuite with a binary release package for any Operating System (Windows, Android, a Linux Distro, etc);  
- If you want to port the driver to a newer version of MAME or any other emulator or core;  
- If you want to port the logic to any other platform or hardware, FPGAs, MCUs, SoCs, embbeded systems, etc;  
  
PS: In any case, just please follow the licenses, this repository have a mix of MIT, MAME and GPL licenses.