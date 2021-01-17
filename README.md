# ![Nokolino](http://www.nikolairadke.de/Nokolino/nokolino_back.jpg)

The DIY-kit Monster. Tiny and cute. And everyone is invited to **contribute**. Nokolino is for everyone. This repository is for the **kit (Bausatz)** edition of Nokolino, easy and fast to build.  
  
*Huch, Englisch? Kann ich nicht. Schnell [hier hin](https://github.com/NikolaiRadke/Nokolino/wiki)*.  
  
What's new?  
**17.01.2021** Only 13 kits are left. Look at Heise Shop [here](https://shop.heise.de/nokolino-bauset).   
-- More news? See the [newsblog](https://github.com/NikolaiRadke/Nokolino/tree/master/NEWS.md).   

![Three NOKOlinos](http://www.nikolairadke.de/Nokolino/nokolinos.png)
  
Like his big brother **Noko**, the little Nokoino delights it's surroundings with cheeky comments. But unlike Noko he is more obstinate - no radio, no display, no frills. Instead of an Arduino he has a small **ATtiny** microcontroller, only an on-off switch and a big button. But he is small, can stay active for days and is, in contrast to his big brother, very easy to build.  
  
Another useful application option would be to use the hardware without the monster suit as a **music box** in an old used doll to bring it back to modern days, maybe with other sounds or songs.  

What does he to - technically? Whenever you press his button, he will laugh. And when he's just turned on, he says something random randomly every statistically 10 minutes. That's it. Quiet a lot for a stuffed monster!  
  
**Nokolino** stands for **No**ra and Ni**ko**s monster - the appendix **lino** describes the small version.  
  
### Notes for non-German Nokolino makers  
  
Right now, the building wiki, the voice sets and the manual are in German. I'll try to translate the wiki and the manual one day. Until then, feel free to ask me for translation, if you need help. **Contribute!** I need an English voice set and English text files. In addition, any other language is welcome, Nokolino is to be cosmopolitan!
  
### Prerequisites
  
Except for some tools and time, the kit is ready to build. The ATtiny is preprogrammed and a the Nokolino male voice set is preinstalled.  
  
If you want to make some changes, Nokolino needs Arduino IDE 1.6.6 or newer (https://www.arduino.cc/en/Main/Software). Copy the folder `Nokolino/src/Nokolino/` into your sketch folder and install ATtiny support. See [how to compile](https://github.com/NikolaiRadke/Nokolino/tree/master/HOW_TO_COMPILE.md) for further instructions. 
  
### Content

```
Nokolino/
Root directory with some explanation files.  
|
├── manual/
|   Nokolino manual in PDF format and a printing version.
|
├── mp3/
|   Voice sets in German. English needed? Contribute!
|   ├── Nokolino/
|   |   Male voice set, spoken by Carsten Caniglia.
|   └── Nokolina/
|       Female voice set, spoken by Norma Anthes.
|
├── schematics/
|   The circuit diagram, the cab 3D-model and the sewing pattern.
|   └── gerber/
|       The gerber files for the PCB to build by your own.
|
└── src/
    ATtiny sketch
    └── Nokolino/
        One file, no libraries, no frills. Just Nokolino. 
```
### Let's get started!

Ready? Great! Let's start here: [German wiki](https://github.com/NikolaiRadke/Nokolino/wiki).  
English wiki will follow. One day...
