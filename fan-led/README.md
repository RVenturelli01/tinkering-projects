# Fan LED

POV display built on an Arduino-controlled fan. LEDs mounted on a spinning arm create persistent images through persistence of vision.

---

## How it works

A magnet is fixed to the outer edge of the fan. As the arm spins, a magnetic sensor detects each full rotation — giving the Arduino the current period and the arm's angular position at any instant. Knowing exactly where the arm is, the firmware fires each LED at the right moment so it always lights up at the same physical position, creating a stable image.

**Bonus:** a radio receiver module on the arm lets a second Arduino (connected to the PC via USB and a radio transmitter) send new image data wirelessly — so images can be changed from the computer in real time.

---

## Version 1 — Single LEDs

<img src="media/fan led montato.jpg" width="100%"/>

### Stick composition

<img src="media/struttura asta.jpg" width="100%"/>

<table width="100%">
<tr>
<td width="33%"><img src="media/striscia led.jpg" width="100%"/></td>
<td width="33%"><img src="media/sensore magnetico.jpg" width="100%"/></td>
<td width="34%"><img src="media/ricevitore radio.jpg" width="100%"/></td>
</tr>
<tr>
<td align="center">LED strip</td>
<td align="center">Magnetic sensor</td>
<td align="center">Radio receiver</td>
</tr>
</table>

### Videos

<video src="https://github.com/user-attachments/assets/432f06eb-4107-4fc7-974f-8471f5fd37e3" controls width="100%"></video>

<video src="https://github.com/user-attachments/assets/d3bceb16-1f6b-45a3-9732-16acfa5aa507" controls width="100%"></video>

<video src="https://github.com/user-attachments/assets/3df0f057-1ebc-47fe-a092-3163ada60823" controls width="100%"></video>

---

## Version 2 — LED strip

Single LEDs replaced by an addressable LED strip: more colors and higher pixel density. No photos of the setup, only the final results.

### Results

<table width="100%">
<tr>
<td width="33%"><img src="media/cuore.jpg" width="100%"/></td>
<td width="33%"><img src="media/random.jpg" width="100%"/></td>
<td width="34%"><img src="media/stella.jpg" width="100%"/></td>
</tr>
</table>

<video src="https://github.com/user-attachments/assets/86bb3cb2-a7fc-43dd-87a4-443ccb2908f9" controls width="100%"></video>
