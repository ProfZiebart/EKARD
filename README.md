# EKARD 
Der **E**inhand **K**nickarm **R**oboter für den **D**esktop. Ein billiger Übungsroboter für die Lehre. Zielpreis unter 200€.

![EKARD](https://github.com/ProfZiebart/EKARD/blob/main/Pictures/EKARD.png)

# Stückliste
-	4x MG90s
-	1x MG995
-	1x 360° Parallax Servo
-	Schleifring
-	Kugellager 608 (Standard Skateboard Lager)
-	Steckerbuchse
-	Platine
-	Bauteile auf der Platine
o	Buchsenleisten
o	Pinheader gerade und gebogen
o	RGB LED
o	3x Wiederstand 220 Ohm
o	1x Wiederstand 10k Ohm
-	Schrauben

Die Idee ist es, mit möglichst wenigen Teilen einen Knickarmroboter auf dem Desktop zu zaubern, der nebenbei zu schwach ist, um jemanden ernsthaft zu verletzen. So kann dieses Projekt in der Lehre zur Veranschaulichung genutzt werden.

Die lokale Robotersteuerung läuft auf einem ESP32 DevKitV4. EIne Anbindung an CAD /CAM ist geplant. Für diesen ESP gibt es eine vorgefertigte Platine (siehe PCB) mit den zugehörigen Anschlüssen. Hierbei ist zu beachten, dass derzeit 2 Anschlüsse unterhalb des ESP32 zu löten sind. Dafür ist die Platine linke Gehäusehälfte.

![EKARD PCB](https://github.com/ProfZiebart/EKARD/blob/main/Pictures/EKARD_pcb.png)
