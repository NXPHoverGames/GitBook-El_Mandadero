---
description: >-
  Guide describing the wire routing and the mechanical assembly of ELM4 Battery
  Pack
cover: ../../../.gitbook/assets/Battery Pack.png
coverY: 95
---

# ELM4 Battery Pack Assembly

## Video

{% embed url="https://youtu.be/rW7MvrMSekk" %}

## Bill of materials

{% embed url="https://a360.co/3lnlFpD" %}

{% hint style="danger" %}
**RISK of fire and personal injury!**\
Use extreme caution when building and working with the battery pack. Do NOT proceed if you are uncomfortable with any aspect of the assembly process.

While these batteries are designed to not explode or burst into flames, still a direct short will melt metal, weld metal together, and could produce sparks, high heat, smoke and result in a secondary fire and/or bodily damage.

Wear protective eyeware. Remove metal rings and other jewelry. \
Ensure your work area is clear from clutter and combustible materials

Have a contingency plan, including egress and a fire extinguisher nearby.
{% endhint %}

{% hint style="warning" %}
**Wrench safety**\
Tightening bolts will require the use of a wrench. Ideally that wrench should be non-conductive. Since a non-conductive wrench impractical, cover the entire wrench with several layers of non-conductive electrical tape to help avoid accidental shorts against neighboring terminals. Cover the box end and open ends of the wrench as well, leaving only the openings to mate with the bolt uncovered. Pay close attention to ways that the wrench movement might still accidentally cause a short.
{% endhint %}

{% hint style="warning" %}
**Wires, plastic and accidental shorts**

The non-conductive plastic components are to help prevent accidental shorts from one side to the other. HOWEVER at all times pay close attention to where any wires or ends of wires may be so there is no accidental shorts that occur with neighboring cells or with the metal enclosure itself.
{% endhint %}

{% hint style="warning" %}
**Assembly order and short circuits**\
The assembly order below is trying to keep the final circuit open as long as possible in the process and leave the easy to access terminals to the last steps to connect. Be sure you understand the potential short circuit/current paths that may take place in the case of an accidental short before attempting this assembly.
{% endhint %}

{% hint style="info" %}
**Battery pack fuse**\
There is a low-level battery pack fuse to protect the batteries and wiring in the case of a dead short, but it still allows a high current of 50-150Amps (depending on the fuse installed) at the full pack voltage. This is a fuse of last resort, and should not be relied upon for primary fusing protection of circuits and devices attached to the battery. Secondary fuses need to be used which are appropriately sized for these loads.\
_Note this fuse must also be type **ignition protected** and of a type rated for full instantaneous pack discharge current "**10K AIC**"_
{% endhint %}

{% hint style="info" %}
**Assembled battery pack, and Anderson style connector safety risk**

Once the pack is assembled the associated risks are reduced. However, there is still the potential for accidental shorts, secondary fires, and personal harm.

When the battery is not in use, disconnecting the back at the "Anderson" two pin connector may be advised. **This connector should be securely covered and not left exposed.**
{% endhint %}

****



## Procedure

1.  Insert and assemble the Bottom Plastic Bed/Rails in the sheet metal Battery Tray\


    <figure><img src="../../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>
2.  Pre-assemble the middle two batteries in each bank as shown below. Don't tighten the two top screws completely yet.&#x20;

    <figure><img src="../../../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

    \- Lock washers MUST be used on the terminal screws\
    \- Tighten well, but do not overtighten the terminal screws.\


    **Note:** The red Ring-tongue terminals do not show the attached wires. These are the cell terminal cables used to report each cell voltage to the BMS.  **Pay attention and protect the loose ends of any of these cell termination wires from potentially shorting to the case or other battery terminals!**\
    \
    \

3.  Insert the remaining 4 batteries to the sides of the pre-assembled pack of two as shown below.\


    <figure><img src="../../../.gitbook/assets/ELM4 Battery Module Assembly - frame at 0m20s.jpg" alt=""><figcaption></figcaption></figure>


4.  Angle the middle copper connectors in place and finish fastening the top two screws in the middle.\


    <figure><img src="../../../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>


5.  Assemble the battery pack ground terminal as shown below. Note this has to be the first ground node in the whole series.\


    <figure><img src="../../../.gitbook/assets/image (3) (4).png" alt=""><figcaption></figcaption></figure>

    **! Ensure any battery cable connectors are protected from shorting with heatshrink !**\
    ****The image above only shows the connector, but this represents the **complete negative side cable** and the other end of the cable should be terminated to the ANDERSON style connector terminal and inserted into the connector housing, or otherwise electrically secured, for safety isolation.\

6.  Insert the middle plastic separator BEFORE assembling the other bank. This will help keep a wrench or other object from shorting when tightening screws on the individual cells.\


    <figure><img src="../../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
7.  Repeat steps 1-4 to install the second six-battery bank.\




    <figure><img src="../../../.gitbook/assets/ELM4 Battery Module Assembly - frame at 0m42s.jpg" alt=""><figcaption></figcaption></figure>
8.  **Pre-assemble the fuse block and cover it with electric tape BEFORE installing it.** Note you will need to slightly insert the lower screw into the copper connector before sliding the whole assembly in place.\


    <figure><img src="../../../.gitbook/assets/ezgif.com-video-to-gif (3).gif" alt=""><figcaption></figcaption></figure>
9.  Finish assembling the fuse on the battery terminal connector and attach the positive battery cable. Note the image shows only the connection of the cable assembly. The complete positive cable should be assembled before attaching here and will have an ANDERSON style crimp connector on the other end. This crimp connector should be installed in the housing the same as the negative side to secure it electrically from accidental shorts.\
    \
    _The intent is that both the negative and positive battery cables are pre-prepared with the HV wires installed in the Anderson connector and or electrically isolated BEFORE  attaching to the battery terminals for safety precautions._ \
    __\
    _!!! COVER the open end of the ANDERSON Connector !!!_\
    _!!! Double check that the Negative and Positive are in the correct pin positions in the Anderson Connector !!!_\
    __\
    __

    <figure><img src="../../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

    \

10. Carefully insert the copper strap connector between banks and fix it in place.\




    <figure><img src="../../../.gitbook/assets/image (16) (3).png" alt=""><figcaption></figcaption></figure>


11. Insert the Top Plastic Plate to finish isolating most of the wiring. Make sure to align the slots with the tabs in the middle plastic plate.\
    It is not shown here, but along with the pack fuse, the battery cables as well as all 13 CT wires will feed through the opening in the plastic plate.\


    <figure><img src="../../../.gitbook/assets/ELM4 Battery Module Assembly - frame at 1m25s.jpg" alt=""><figcaption></figcaption></figure>
12. Install the fuse access panel to the plastic plate using four M5-0.8x10 button head cap screws.  (Alternatively it is also acceptable to install this to the plastic plate first) \


    <figure><img src="../../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>
13. Install the plastic lid to protect the fuse while you do the rest of the wiring.\


    <figure><img src="../../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>


14. Put the side panels in place and fix them using nine M3-0.5x5 screws per panel. \
    (Please ensure the edge flange overlap is correct - the short vertical bends should be on the outside of the larger box flange)\
    &#x20;

    <figure><img src="../../../.gitbook/assets/ELM4 Battery Module Assembly - frame at 1m48s.jpg" alt=""><figcaption></figcaption></figure>


15. Prepare the remaining accessories and components that will go fixed in the top metal plate. We recommend, additional to the BMS, to use distribution poles, a DC/DC converter and a fuse block to distribute the power to the different accessories in El Mandadero. An example set of components is shown here and there are pre-drilled holes for these example parts.\
    \
    Your specific component mounting requirements may vary. Drill mounting holes in the top plate as necessary - you will likely also need to make clearance holes in the plastic plate to match.\




    <figure><img src="../../../.gitbook/assets/ELM4 Battery Module Assembly - frame at 1m59s.jpg" alt=""><figcaption></figcaption></figure>

    <figure><img src="../../../.gitbook/assets/ELM4 Battery Module Assembly - frame at 2m5s.jpg" alt=""><figcaption><p>Showing 3d printed cover for MR-BMS771</p></figcaption></figure>



    <figure><img src="../../../.gitbook/assets/ELM4 Battery Module Assembly - frame at 2m7s.jpg" alt=""><figcaption><p>Make sure to install the little plastic standoff for the SB50 connector.</p></figcaption></figure>
16. Sit the metal plate on top of the battery pack but don't fix it yet in case you need to make adjustments. At this point you will also need to manipulate your wiring through the opening for the fuse block in the metal lid. Be sure to be careful in this step and always have ANY of your live wire ends isolated and protected until you make the final connection.\


    <figure><img src="../../../.gitbook/assets/ELM4 Battery Module Assembly - frame at 2m11s.jpg" alt=""><figcaption></figcaption></figure>


17. You can now:\
    \- ensure your MR-BMS771 is correctly prepared for 12S operation\
    \- connect the CT wires to the MR-BMS771 header\
    \- affix the battery-end Anderson-type SB50 connector in its standoff using two M3-0.5x15 button head cap screws.\
    \- pre-wire BMS to terminal blocks, DCDC converter to terminal blocks and 12V fusebox \


    <figure><img src="../../../.gitbook/assets/ELM4 Battery Module Assembly - frame at 2m29s.jpg" alt=""><figcaption></figcaption></figure>


18. Assemble the BMS-end Anderson-Style SB50 connector to its press-fit plastic slider as shown below.\


    <figure><img src="../../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>


19. You can now connect the HV wires to the BMS. NOTE: The BMS should be pre-wired to the terminal block. If you have anything else to wire, like 12V accessories, also do it before this step.\


    <figure><img src="../../../.gitbook/assets/image (1) (1).png" alt=""><figcaption><p><br></p></figcaption></figure>
20. Fix the Top Metal Plate in place using fourteen M3-0.5x5 button head cap screws.\
    _Generally speaking you will want to loosely install all the screws initially to ensure you have room to move and align them all with the panels first before going around again for a final tightening._\


    <figure><img src="../../../.gitbook/assets/ELM4 Battery Module Assembly - frame at 2m46s.jpg" alt=""><figcaption></figcaption></figure>

## Assembly notes

{% hint style="danger" %}
* Be extremely cautious during the whole process. Do not proceed unless you understand the potential risks.
* Make sure to always isolate the high voltage terminals until you are certain everything is correctly and securely assembled, only then finally power the BMS.
{% endhint %}
