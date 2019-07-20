# SAKURA, Amiga pcmcia sram
4MB of Fast RAM for unexpanded Amiga 600/1200.
Original desig by Jarosław Bieliński and Radosław Kujawa.
The informations about the original version of this board can be found here: https://github.com/Sakura-IT/ppa-pcmcia-sram

Since the original version, some components, like the RAM, are became difficult to find, so, many revisions of this board was made in order to use available components.
In 2018 the project was updated again and ported to KiCad by jensma: https://github.com/jensma/ppa-pcmcia-sram
This revision is based on his work.

![Board](https://raw.githubusercontent.com/screwbreaker/ppa-pcmcia-sram/master/docs/render-top.png)

### Summary
Some components like the RAM are available but not cheap. On the jensma revision also the PCB was not cheap, because he used small tracks and vias.
The main goal of this revision is to made the PCB as cheaper as possible. This make this expansion a little more affordable.

#### BOM
- C14,C3,C5,C6,C7,C8,C9,C10,C11,C12,C13,C4 100nF 0805 ceramic capacitor
- C1,C2: >=10uF >=6,3V 1206 tantalum capacitor
- U1: LM1117-3.3 voltage regulator
- IC2,IC3, IC4 74LCX245MTC
- IC5,IC6,IC7: 74LCX541TTR
- IC1: AS6C3216-55, SRAM
- IC8: XC9536XL_44VQ CPLD
- PCMCIA connector 95622-004LF
- SW1: SW_SPDT_CK-JS102011SAQN

### Installation
Since this board don't have a proper PCMCIA case it must be inserted carefully.
Do not apply too much force, or the pin iside the Amiga connector can be damaged.
There is a maker on the board to identify the upper side.

### License
This board is Open Hardware. If you make any modifications to the board, please contribute them back.

### Disclaimer
This board is provided to you 'as is' and without any express or implied warranties whatsoever with respect to its functionality, operability or use, including, without limitation, any implied warranties of merchantability, fitness for a particular purpose or infringement. We expressly disclaim any liability whatsoever for any direct, indirect, consequential, incidental or special damages, including, without limitation, lost revenues, lost profits, losses resulting from business interruption or loss of data, regardless of the form of action or legal theory under which the liability may be asserted, even if advised of the possibility or likelihood of such damages.

### Thanks
- A special Thanks to: [EmberHeavyIndustries](https://github.com/EmberHeavyIndustries) for the help in the development.
- DanyPPC who started the discussion, [SukkoPera](https://github.com/SukkoPera), Mck, and all the other guys on the Italian Amiga forum [Amigapage](https://www.amigapage.it/index.php?op=v&pl=forum&id=F012019-2-9&page=1)