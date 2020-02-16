# Installing a Standalone Fail-Secure Electric Lock #

**You will need:**

* Kisi Controller Pro (comes with a 24V Universal AC power supply)- **Included** in the Kisi Controller Pack
* 12 or 24V DC [electric strike or magnetic lock](https://www.getkisi.com/guides/electronic-locks) - **NOT** Included
* Ethernet Cable - **NOT** Included
* Low Voltage Wires - **NOT** Included

**IMPORTANT**

The Kisi Controller Pro only supplies up to 4 Amps total for the door locks that are drawing power from the circuit board. If you wish to power up more doors, DO NOT exceed a total of 4 Amps for each Kisi Controller Pro.

Example: If you have two electric strikes that draw 12V/2 Amps from Kisi Pro, you CANNOT power anymore locks from the circuit board. You can still wire another two door locks to the Kisi Controller Pro, but only from their own separate power supply and as DRY contacts.


**ALSO NOTE:**

Kisi Controller Pro does NOT support AC wiring, so make sure the lock can work on DC.

Here's a short video on the wiring:

<iframe width="560" height="315" src="https://www.youtube.com/embed/AR7dXvml0TE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



**SEQUENCE**

![Wiring Your Kisi Controller to a Fail-Secure Lock](https://help.kisi.io/hc/article_attachments/360052318854/Standalone_fail_secure_electric_lock.PNG)

*STEP 1*

 * Wire one of the four relays to the fail-secure lock on the door. This is a wet contact relay which will require positive wires to run to the 12V or 24V (Depending on your lock) and negative to NO (Normally Open).

 * Be sure that you do **NOT** connect the door lock to GND and NC (Normally Closed). Such a configuration will burn out the fail-secure lock over time.

*STEP 2*

 * Configure the jumper wire to run from GND (Ground) to COM (Common).

*STEP 3*

 * Next, connect the power. Black wire to GND (Ground) and white wire to 24V. Once complete, a blue light should come on.

*STEP 4*

 * Finally, you will plug in your ethernet cable. You should see a green blinking light on the top right hand corner of the board. This indicates that the Kisi Controller Pro is online.

### IS THERE SOMETHING WRONG? ###

If the light on the board is not green, or have any other issues, please refer to this [troubleshooting guide.](https://help.kisi.io/hc/en-us/articles/115009339068-Network-Settings-for-Controller-Pro-)
