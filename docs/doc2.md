---
id: doc2
title: Installing an External Power Supply & Fail Safe Electric Lock
---

Read [this before you install the Kisi Controller.](https://help.kisi.io/hc/en-us/articles/115009576508-Before-Installing-Kisi-)

**You will need:**

* Kisi Controller Pro (comes with a 24V Universal AC power supply)- **Included** in the Kisi Controller Pack
* 12 or 24V DC [fail safe electric strike or magnetic lock](https://www.getkisi.com/guides/electronic-locks) - **NOT** Included
* Ethernet Cable - **NOT** Included
* Low Voltage Wires - **NOT** Included
* [External Power Supply](https://www.altronix.com/products/AL600ULACM) for lock - **NOT** Included
* Push to exit button/motion sensor - **NOT** Included
* Keypad - **NOT** Included

**NOTE**

The wiring should also run to a keypad outside the space and a Request to Exit (REX) inside the space. A keypad should be used as a back-up mode of access in case internet goes down. A REX allows an occupant to exit the door without using Kisi, and would refer to either a motion sensor or a push-to-exit button.  

![Installation Diagram for an External Powered Fail Safe electric Lock](https://help.kisi.io/hc/article_attachments/360011143214/Screen_Shot_2018-08-24_at_9.34.06_AM.png)

Here is a video on it:

<iframe width="560" height="315" src="https://www.youtube.com/embed/PRpPIUCUwh0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**SEQUENCE**

*STEP 1*

Wire one of the four door relays to the external power supply and the fail-safe lock on your door. Since you will be wiring the relay as a dry contact, start by wiring the relay to the power supply from **COM** (Common) and **NO** (Normally Open) on the Kisi relay to the **GND** (Ground) and **IN** (Input) of the power supply.  


*STEP 2*

Next, run the negative wires (-) to **COM** (Common) and run the positive ones (+) to **NC** (Normally Closed) from the Power Supply back to the lock.

*STEP 3*

Wire your Request to Exit (REX) to **IN1** (Input 1) and **GND** (Ground) in the REX component on the Kisi controller.

*STEP 4*

Connect the external power supply to a [fire alarm system.] (https://help.kisi.io/hc/en-us/articles/360037151673-Connecting-Kisi-to-Fire-Alarms) This is in accordance to safety code - when the fire alarm triggers, power to the Kisi Controller Pro will be interrupted and the doors will automatically unlock.  Kisi recommends connecting fire alarms to the external power supply as that unit has its own fire alarm control panel (FACP) which shuts down the locks when the fire alarm is triggered.

*STEP 5*

Once complete, power the Kisi Controller Pro using provided power supply and input. A blue light should come on if powered.

Next, plug in the Ethernet cable. You should see a green blinking light on the top right hand corner of the board. This indicates that the Kisi Controller Pro is online.

### IS THERE SOMETHING WRONG? ###

If the light on the board is not green, or have any other issues, please refer to this [troubleshooting guide.](https://help.kisi.io/hc/en-us/articles/115009339068-Network-Settings-for-Controller-Pro-)
