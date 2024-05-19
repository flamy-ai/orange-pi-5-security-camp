[thermal pad]: /more/terminology.md#thermal-pad "Soft pad that conducts heat away from computer chips."
[heatsink]: /more/terminology.md#heatsink "Large hunk of metal that absorbs heat and cools computer chips."
[soc]: /more/terminology.md#soc-system-on-chip "System-on-Chip: includes multiple processors with different functions in a single chip."
[cpu]: /more/terminology.md#cpu-central-processing-unit "Central Processing Unit: main computing chip, the brains."
[ram]: /more/terminology.md#ram-random-access-memory "Random-Access Memory: stores data the computer is currently working on."
[gpu]: /more/terminology.md#gpu-graphics-processing-unit "Graphics Processing Unit: processes visual tasks, like games."
[npu]: /more/terminology.md#npu-neural-processing-unit "Neural Processing Unit: processes neural networks (AI)"

<h1 align=center>Assembling Your Orange Pi 5</h1>

<br>

<h2 align=center>Connect Ethernet Cables</h2>

1. Get out your [PoE] [Network Switch]
2. Attach the foam feet to the bottom of the switch
3. Take the power cord for the [network switch] and plug it into the power outlet and the switch.
4. Connect a long ethernet cable to port 4 of your [network switch] and our camp switch (this is how we connect the [Orange Pi 5] to the internet).
5. Connect a short ethernet cable to port 1 of your network switch and the end of the [PoE] Splitter USB Type C with only one plug.

   <img width=40% src="/src/img/poe-splitter-type-c-one-port.jpg">
6. Connect another short ethernet cable to the end of the [PoE] Splitter USB Type C with 2 plugs.

   <img width=40% src="/src/img/poe-splitter-type-c-two-ports.jpg">
7. Connect the DC barrel jack to USB C cable to the [PoE] Splitter USB Type C.

   <img width=40% src="/src/img/poe-splitter-type-c-with-power-cable.jpg">
8. We purposefully left one end of the USB C cable and one end of the Ethernet cable from the [PoE] Splitter USB Type C unplugged.

<br><br><br>

<h2 align=center>Attaching the M.2 SSD</h2>

1. You will need your [Orange Pi 5] and the [M.2] [SSD]. You will also need the screwdriver that was in the box with the [Orange Pi 5] case.
2. Find the tiny bag with a screw, plastic washer, and nut that came with the [Orange Pi 5].

   <img width=40% src="/src/img/orange-pi-m.2-fasteners.jpg">
3. Insert the [M.2] [SSD] at a 30-degree angle into the [M.2] slot on the bottom of the [Orange Pi 5].

   <img width=60% src="/src/img/orange-pi-m.2-insertion.jpg">
4. Place the washer on the hole in the [motherboard] below the M.2 [SSD] and place the screw through the washer and hole, making sure it holds down the [M.2] [SSD].

   <img width=60% src="/src/img/orange-pi-m.2-using-fasteners.jpg">
5. Hold the screw in place and turn over the board. Find where the screw is poking through to the other side. Place the nut on the screw sticking through and tighten it clockwise (righty-tighty).

   <img width=60% src="/src/img/orange-pi-m.2-side-view.jpg">
6. Now you can hold the nut with one hand and tighten the screw using the screwdriver from the [Orange Pi 5] case.

<br><br><br>

<h2 align=center>Applying Thermal Pads</h2>

1. Find the bag included with the [Orange Pi 5] case containing the [thermal pad]s and the foam feet.

   <img width=40% src="/src/img/orange-pi-case-thermal-pad-and-feet-bagged.jpg">
2. Remove the [thermal pad]s from the bag so that we can apply them.

   <img width=40% src="/src/img/orange-pi-case-thermal-pads.jpg">
3. The [thermal pad]s contact the big, square, shiny [SoC] and the 2 smaller, rectangular, black [RAM] chips on the motherboard. The other side of the [thermal pad]s contact the [heatsink] on the case.

   <img width=40% src="/src/img/orange-pi-chips-to-cool.jpg">
   <img width=40% src="/src/img/orange-pi-case-heatsink.jpg">

<br>

<h3 align=center>You will now apply the thermal pads one at a time.</h3>
<p align=center>If you damage or destroy any thermal pads just show us and we'll help you.</p>

<br>

4. Take one of the two smaller [thermal pad]s and peel off the plastic film to expose only one side of the [thermal pad].

   <img width=40% src="/src/img/orange-pi-thermal-pad-1-peel-1.jpg">
5. Carefully, preferably without touching the exposed side, (even if you touch it, use it,) lower the [thermal pad] onto the black [RAM] chip.

   <img width=40% src="/src/img/orange-pi-thermal-pad-1-application.jpg">
6. Now you should very carefully align the [thermal pad] with the white, dashed lines on the [motherboard]. Gently push sideways on the edge of the [thermal pad] to align it.

   <img width=40% src="/src/img/orange-pi-thermal-pad-1-alignment.jpg">
7. After you have aligned the thermal pad, lay your finger (don't poke it with your fingernail, look at the picture below) on the [thermal pad] (which still has a plastic film on it, do not peel yet) and apply gentle but firm, downward force so that the [thermal pad] will stay on the [RAM] chip.

   <img width=40% src="/src/img/orange-pi-thermal-pad-1-pressure.jpg">
8. <details>
      <summary>
         Click to expand this dropdown. (This is a repeat of steps 4-7). Complete this before moving on.
      </summary>
      <p>
      
      1. Take the largest [thermal pad] and peel off the plastic film to expose only one side of the [thermal pad].

         <img width=40% src="/src/img/orange-pi-thermal-pad-2-peel-1.jpg">
      2. Carefully, preferably without touching the exposed side, (even if you touch it, use it,) lower the [thermal pad] onto the shiny [SoC].

         <img width=40% src="/src/img/orange-pi-thermal-pad-2-application.jpg">
      3. Now you should very carefully align the [thermal pad] with the white, dashed lines on the [motherboard]. Gently push sideways on the edge of the [thermal pad] to align it.

         <img width=40% src="/src/img/orange-pi-thermal-pad-2-alignment.jpg">
      4. After you have aligned the thermal pad, lay your finger (don't poke it with your fingernail, look at the picture below) on the [thermal pad] (which still has a plastic film on it, do not peel yet) and apply gentle but firm, downward force so that the [thermal pad] will stay on the [SoC].

         <img width=40% src="/src/img/orange-pi-thermal-pad-2-pressure.jpg">
      5. Take the remaining smaller [thermal pad] and peel off the plastic film to expose only one side of the [thermal pad].

         <img width=40% src="/src/img/orange-pi-thermal-pad-3-peel-1.jpg">
      6. Carefully, preferably without touching the exposed side, (even if you touch it, use it,) lower the [thermal pad] onto the black [RAM] chip.

         <img width=40% src="/src/img/orange-pi-thermal-pad-3-application.jpg">
      7. Now you should very carefully align the [thermal pad] with the white, dashed lines on the [motherboard]. Gently push sideways on the edge of the [thermal pad] to align it.

         <img width=40% src="/src/img/orange-pi-thermal-pad-3-alignment.jpg">
      8. After you have aligned the thermal pad, lay your finger (don't poke it with your fingernail, look at the picture below) on the [thermal pad] (which still has a plastic film on it, do not peel yet) and apply gentle but firm, downward force so that the [thermal pad] will stay on the [RAM] chip.

         <img width=40% src="/src/img/orange-pi-thermal-pad-3-pressure.jpg">
      </p>
   </details>

<br><br><br>

<h2 align=center>Putting on the Case</h2>

1. Get all the parts for the case (what was in the box for the case).
2. **[Optional Step]** Install the rubber grommets in the antenna holes. (We aren't using WiFi so we don't have antennas.)
3. 

<br><br><br>

<h2 align=center>Section</h2>

1. Do this
2. and this
    1. Note: blah
    2. subpoint
3. last

<br><br><br>

<h2 align=center>Section</h2>

1. Something
2. more

<br><br><br>

<table align=center>
    <tr>
        <td>

[Go Back](/instructions/day-1/os-install.md)
        </td>
        <td>
[Table of Contents](/README.md)
        </td>
        <td>
[Continue](/README.md)
        </td>
    </tr>
</table>
