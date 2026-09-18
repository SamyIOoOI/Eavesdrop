<h1 align="center">Eavesdrop</h1>

![img](Graphics/senderpcb.png)


### <p align="center">[Main Features](#main-features) **-** [Usage](#usage-of-eavesdrop) **-** [PCB & Schematic](#design) **-** [Gerber Files](/Eavesdrop/Gerber%20Files/) **-** [Kicad (Schematic & PCB)](/Eavesdrop/Kicad%20Source%20Files/) **-** [Credits](#credits)</p>

## We all know about the little radio wave recorders, called FM bugs. However, not everyone, -including me not so long ago- knows about current carrier bugs.


**A "current carrier bug" is a spy tool that records the sound inside the area its plugged in and sends it back through the building's AC directly, evading RF detection as awhole. So your own electricity becomes a medium for spying on you.*

----------------

**<p align="center">No matter where you are. The bug listens as long as there's electricity following in the bugged device.<p>**

---------------


## Main Features

- Undetectable (via RF Detectors that are commonly used)
- Secretive (but requires prior access to the room)

- **Can be planted into any device, your lamp, your tv, your pc, ANYTHING can become a bug with one plug.**

## Usage of Eavesdrop

1- Insert it into either the outlet or any device that takes in power from the outlet and make sure the microphone jack is connected to proper element such as an electret mic.

2- Connect the passive & active AC wires to their respective locations via the male header on the pcb, each one reads if its N (neutral) or L (live). 
Reversal could cause heavy damage. Use a test screw driver to make sure you're connecting the right ones.

3- connect the receiver when required to listen to the broadcast to an outlet that has the same grid as the target room/building.

4- Make sure that both the receiver and the sender are at the same wavelength via calibrating the appropriate potentiometers.

5- Use the volume control knob to increase/decrease th sound level.


<br>


<p align="center">However It is safe to note that usage of Eavesdrop or any other spying device is illegal when taken out of personal hobbiest boundaries within local areas. (Interfering with those on your grid might still penalitize you) <br><br> I hold no responsiblity on the misuse of this project with ill intentions. <br><br> Sharing of my work is done for the sake of open-sourcing, eduction and self-learning. Not to inflict harm.<p>


## Design

Eavesdrop Sender Schematic
![img](Graphics/senderschematic.png)

Eavesdrop Sender PCB
![img](Graphics/senderrawpcb.png)

Eavesdrop Sender PCB (Model)
![img](Graphics/senderpcb.png)


Eavesdrop Receiver Schematic
![img](Graphics/receiverschematic.png)

Eavesdrop Receiver PCB
![img](Graphics/receiverpcb.png)


Eavesdrop Receiver PCB (Model)
![img](Graphics/pcbreceivermodel.png)


## Credits

Made by SamyIOoOI on github under the GPL 3.0 Licence.

![img](Graphics/kicad.png)