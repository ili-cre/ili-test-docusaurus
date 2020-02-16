# Installing an External Power Supply & Fail Safe Electric Lock With REX & Motion Sensor #

**You will need:**

* Kisi Controller Pro (comes with a 24V Universal AC power supply)- **Included** in the Kisi Controller Pack
* 12 or 24V DC [fail safe electric strike or magnetic lock] (https://www.getkisi.com/guides/electronic-locks) - **NOT** Included
* Ethernet Cable - **NOT** Included
* Low Voltage Wires - **NOT** Included
* [External Power Supply] (https://www.altronix.com/products/AL600ULACM) for lock - **NOT** Included
* Push to exit button/motion sensor - **NOT** Included
* Keypad - **NOT** Included

! (https://help.kisi.io/hc/article_attachments/360053218093/REX_and_Motion_Sensor.png)

Here's a short video on it:

<iframe width="560" height="315" src="https://www.youtube.com/embed/H0vQgyN_pN0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## CONNECTION SEQUENCE ##

*STEP 1*
Connect the negative (-) lead from the Maglock to the Normally Closed (NC) connection on the 'Push to Exit' button.

*STEP 2*
Connect the Common (COM) lead on your 'Push to Exit' to the Common (COM) connection of the Motion Sensor.

*STEP 3*
Connect the Normally Closed (NC) connection of the Motion Sensor to the Common (COM) connection of the Power Supply's output.

*STEP 4*
Connect the positive (+) lead from the Maglock to the Normally Closed (NC) output connection of the Power Supply's output.

*STEP 5*
Connect the low voltage wiring from Common (COM) on the Kisi controller to Ground (GND) on the Power Supply's input, and Normally Open (NO) on the Kisi controller to In (IN) on the Power Supply's input.
