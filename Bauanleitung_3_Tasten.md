# USB Maus Bausatz

<!--
SPDX-FileCopyrightText: 2015 Susanne Jordan <jordan@nager-it.de>
SPDX-FileCopyrightText: 2025 Joram Ulmke <joramulmke@proton.me>
SPDX-FileCopyrightText: 2025 - 2026 Robin Vobruba <hoijui.quaero@gmail.com>

SPDX-License-Identifier: CC-BY-SA-4.0
-->

Aktuell (Stand 12/2025) verschicken wir 3-tastige Bausätze.

## Inhaltsverzeichnis

- [Übersicht der Einzelteile](#übersicht-der-einzelteile)
- [Benötigte Werkzeuge](#benötigte-werkzeuge)
- [Platine bestücken](#platine-bestücken)
- [Unterschale bearbeiten für dritte Taste](#unterschale-bearbeiten-für-dritte-taste)
- [Sensor-Folie abziehen](#sensor-folie-abziehen)
- [Finaler Zusammenbau](#finaler-zusammenbau)

## Übersicht der Einzelteile

![Übersicht](image/overview.jpg)

| | |
| --- | ------ |
| ![Bodenplatte](image/bodenplatte.jpg) | Bodenplatte |
| ![Oberschale](image/oberschale.jpg) | Oberschale |
| ![Rechte Taste](image/rechte-maustaste.jpg) | Rechte Taste |
| ![Linke Taste](image/linke-maustaste.jpg) | Linke Taste |
| ![Hölzernes Mausrad](image/mausrad.jpg) | Hölzernes Mausrad |
| ![Optik (Linse)](image/linse.jpg) | Optik (Linse) |
| ![USB Kabel](image/usb-kabel.jpg) | USB Kabel |
| ![Torx (Vielzahn) Schraube](image/torx.jpg) | Torx (Vielzahn) Schraube (2 x T9 und 2 x T10) |
| ![2 x für Maustasten](image/schraube-maustaste.jpg) | 2 x für Maustasten |
| ![2 x Schraube für Gehäuse](image/schraube-gehäuse.jpg) | 2 x Schraube für Gehäuse |
| ![2 x Kondensatoren 0,1µF](image/kondensator-01.jpg) | 2 x Kondensatoren 0,1µF |
| ![Kondensator 10µF](image/kondensator-10.jpg) | Kondensator 10µF |
| ![LED Grün / Rot](image/lde-grün.jpg) | LED Grün / Rot |
| ![5 x Drahtbrücken](image/drahtbruecken.jpg) | 5 x Drahtbrücken, da Platine einseitig |
| ![2 x Schalter für Linke und Rechte Taste](image/schalter.jpg) | 2 x Schalter für Linke und Rechte Taste |
| ![Schalter für Mitteltaste](image/schalter-mitteltaste.jpg) | Schalter für Mitteltaste |
| ![Drehgeber für Mausrad](image/drehgeber.jpg) | Drehgeber für Mausrad |
| ![Optischer Sensor & Prozessor](image/chip.jpg) | Herzstück der Maus: Optischer Sensor, Prozessor und USB Schnittstelle |
| ![Gleitplättchen](image/gleitplättchen.jpg) | Gleitplättchen |

![Platine](image/pcb-6-overview.jpg)

Platine (Vorder- und Rückseite mit Erklärung)

## Benötigte Werkzeuge

| | |
| --- | ------ |
| ![Elektronik (fein) Seitenschneider](image/Seitenschneider.jpg) | Elektronik (fein) Seitenschneider |
| ![Lötstation](image/loetstation.jpg) | Lötstation |
| ![Torx T9 Bit](image/torx-t9.jpg) | Torx T9 Bit |
| ![Torx T10 Bit](image/torx-t10.jpg) | Torx T10 Bit |
| ![Bleifreies Lötzinn](image/bleifreies-lötzinn.jpg) | Bleifreies Lötzinn |

## Platine bestücken

Beim Bestücken der Platine gibt es eine Reihenfolge, welche einzuhalten äußerst ratsam ist.
Die Bauteile werden immer von flach (z.B. Drahtbrücken, Widerstände, …)
nach hoch (z.B. Schalter, Kondensatoren, …) sortiert.
Als vorletztes werden Anschluss-Leitungen verlötet,
da diese ansonsten während dem Bestücken und Löten stören können.
Der optische Maussensor/Prozessor wird ganz zum Schluss bestückt.

> **WARNUNG** Immer erst ein Bein eines Bauteiles verlöten
> und dann den korrekten Sitz kontrollieren
> (z.B.: liegen die Bauteile/Drähte sauber auf der Platine auf?).

### Schlechtes Beispiel

<img src="image/pcb-9-bad-example.jpg" alt="" width="90%">
\includegraphics[width=0.9\textwidth]{image/pcb-9-bad-example.jpg}

### Drahtbrücken bestücken

<img src="image/pcb-10-jumpers.jpg" alt="" width="90%">
\includegraphics[width=0.9\textwidth]{image/pcb-10-jumpers.jpg}

### Kondensatoren und LED bestücken

<img src="image/pcb-11-capacitors-and-leds.jpg" alt="" width="90%">
\includegraphics[width=0.9\textwidth]{image/pcb-11-capacitors-and-leds.jpg}

### Taster bestücken

<img src="image/pcb-12-switch-keys.jpg" alt="" width="90%">
\includegraphics[width=0.9\textwidth]{image/pcb-12-switch-keys.jpg}

### Elko bestücken

<img src="image/pcb-13-electrolytic-capacitor.jpg" alt="" width="90%">
\includegraphics[width=0.9\textwidth]{image/pcb-13-electrolytic-capacitor.jpg}

### Drehgeber bestücken

<img src="image/pcb-14-rotary-encoder.jpg" alt="" width="90%">
\includegraphics[width=0.9\textwidth]{image/pcb-14-rotary-encoder.jpg}

### USB Kabel

1. Die Kabelisolation ca. 25mm vom Ende her (Hülle)
   mit einem nicht zu scharfen Messer vorsichtig einkerben.

   <img src="image/usb-1-1.jpg" alt="" height="150">
   \includegraphics[width=0.2\textwidth]{image/usb-1-1.jpg}

2. Die Kabelisolation (Hülle) vorsichtig (mit dem Daumennagel) abziehen.

   | | |
   | --- | ------ |
   | ![Isolation 1](image/usb-1-2-1.jpg) | ![Isolation 2](image/usb-1-2-2.jpg) |

3. Die Drahtschirmung vorsichtig abwickeln
   (die feinen Drähte können stechen wie Nadeln).

   <img src="image/usb-1-3.jpg" alt="" height="150">
   \includegraphics[width=0.4\textwidth]{image/usb-1-3.jpg}

4. Drahtschirm verdrillen und den Folienschirm abwickeln.

   <img src="image/usb-1-4.jpg" alt="" height="150">
   \includegraphics[width=0.4\textwidth]{image/usb-1-4.jpg}

5. Die Füllfäden mit einem Messer oder Seitenschneider abschneiden.

   <img src="image/usb-2-5.jpg" alt="" height="150">
   \includegraphics[width=150pt]{image/usb-2-5.jpg}

6. Das Ende des verdrillten Schirmgeflechtes verzinnen.

   <img src="image/usb-2-6.jpg" alt="" height="150">
   \includegraphics[width=150pt]{image/usb-2-6.jpg}

7. Die Isolation der farbigen Adern an den Enden vorsichtig maximal 3mm entfernen.

   <img src="image/usb-2-7.jpg" alt="" height="150">
   \includegraphics[width=150pt]{image/usb-2-7.jpg}

8. Die Adern-Enden verzinnen.
   Die Isolation zieht sich durch die Hitze noch weiter zurück.

   <img src="image/usb-2-8.jpg" alt="" height="150">
   \includegraphics[width=150pt]{image/usb-2-8.jpg}

9. Nun kann das USB Kabel in die Platine eingelötet werden.

   <img src="image/pcb-17-usb-cable.jpg" alt="" width="80%">
   \includegraphics[width=0.9\textwidth]{image/pcb-17-usb-cable.jpg}

Eine gute Lötstelle zeichnet sich durch eine glänzende Oberfläche aus
(mit bleihaltigem Lötzinn).
Bleifreies Lötzinn ergibt immer eine matte Oberfläche:

<img src="image/pcb-18-bad-example-2.jpg" alt="" width="70%">
\includegraphics[width=0.9\textwidth]{image/pcb-18-bad-example-2.jpg}

### Sensor bestücken

<img src="image/pcb-19-processor-sensor.jpg" alt="" width="90%">
\includegraphics[width=0.9\textwidth]{image/pcb-19-processor-sensor.jpg}

> **WARNUNG** Um Schäden des Sensors durch elektrische Ladungen zu verhindern,
> sollte man sich vor dem Berühren des Sensors selbst entladen haben,
> z.B. an der Erdung der Steckdose oder dem Metall eines Heizkörpers.

## Unterschale bearbeiten für dritte Taste

In der rechten Aufhängung des Scrollrad muss unten das hochstehende Mittelteil entfernt werden, damit das Drücken der dritten Taste funktioniert.

<img src="image/ausbrechen-dritte-taste.jpg" alt="" height="400">
\includegraphics[width=0.5\textwidth]{image/ausbrechen-dritte-taste.jpg}

## Sensor-Folie abziehen

Ziehe nun vorsichtig die Folie vom Sensor (Chip).

<img src="image/Sensor-Folie.jpg" alt="" height="400">
\includegraphics[width=0.9\textwidth]{image/Sensor-Folie.jpg}

## Finaler Zusammenbau

| | |
| --- | ------ |
| 1. | ![Zusammenbau 1](image/zusammenbau-1.jpg) |
| 2. | ![Zusammenbau 2](image/zusammenbau-2.jpg) |
| 3. | ![Zusammenbau 3](image/zusammenbau-3.jpg) |
| 4. | ![Zusammenbau 4](image/zusammenbau-4.jpg) |

Wenn alles richtig gemacht wurde und keine Kurzschlüsse gelötet wurden,
kann die korrekte Funktion der Maus am PC getestet werden.
Nun haben wir eine 3-Tasten USB-Maus,
welche einmalig auf der Welt ist,
da sie selbst zusammengebaut wurde.
