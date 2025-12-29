# USB Maus Bausatz

Aktuell (Stand 12/2025) verschicken wir 3-tastige Bausätze.

## Inhaltsverzeichnis

- [Übersicht der Einzelteile](#übersicht-der-einzelteile)
- [Benötigte Werkzeuge](#benötigte-werkzeuge)
- [Platine bestücken](#platine-bestücken)
- [Unterschale bearbeiten für dritte Taste](#unterschale-bearbeiten-für-dritte-taste)
- [Sensor-Folie abziehen](#sensor-folie-abziehen)
- [Finaler Zusammenbau](#finaler-zusammenbau)

## Übersicht der Einzelteile

![Übersicht](image/overview.png)

| | |
| --- | ------ |
| ![Bodenplatte](image/bodenplatte.png) | Bodenplatte |
| ![Oberschale](image/oberschale.png) | Oberschale |
| ![Rechte Taste](image/rechte-maustaste.png) | Rechte Taste |
| ![Linke Taste](image/linke-maustaste.png) | Linke Taste |
| ![Hölzernes Mausrad](image/mausrad.png) | Hölzernes Mausrad |
| ![Optik (Linse)](image/linse.png) | Optik (Linse) |
| ![USB Kabel](image/usb-kabel.png) | USB Kabel |
| ![Torx (Vielzahn) Schraube](image/torx.png) | Torx (Vielzahn) Schraube (2 x T9 und 2 x T10) |
| ![2 x für Maustasten](image/schraube-maustaste.png) | 2 x für Maustasten |
| ![2 x Schraube für Gehäuse](image/schraube-gehäuse.png) | 2 x Schraube für Gehäuse |
| ![2 x Kondensatoren 0,1µF](image/kondensator-01.png) | 2 x Kondensatoren 0,1µF |
| ![Kondensator 10µF](image/kondensator-10.png) | Kondensator 10µF |
| ![LED Grün / Rot](image/lde-grün.png) | LED Grün / Rot |
| ![5 x Drahtbrücken](image/drahtbruecken.png) | 5 x Drahtbrücken, da Platine einseitig |
| ![2 x Schalter für Linke und Rechte Taste](image/schalter.png) | 2 x Schalter für Linke und Rechte Taste |
| ![Schalter für Mitteltaste](image/schalter-mitteltaste.png) | Schalter für Mitteltaste |
| ![Drehgeber für Mausrad](image/drehgeber.png) | Drehgeber für Mausrad |
| ![Optischer Sensor & Prozessor](image/chip.png) | Herzstück der Maus: Optischer Sensor, Prozessor und USB Schnittstelle |
| ![Gleitplättchen](image/gleitplättchen.png) | Gleitplättchen |

![Platine](image/assembly-kit-site-6-pcb-overview.png)

Platine (Vorder- und Rückseite mit Erklärung)

## Benötigte Werkzeuge

| | |
| --- | ------ |
| ![Elektronik (fein) Seitenschneider](image/Seitenschneider.png) | Elektronik (fein) Seitenschneider |
| ![Lötstation](image/loetstation.png) | Lötstation |
| ![Torx T9 Bit](image/torx-t9.png) | Torx T9 Bit |
| ![Torx T10 Bit](image/torx-t10.png) | Torx T10 Bit |
| ![Bleifreies Lötzinn](image/bleifreies-lötzinn.png) | Bleifreies Lötzinn |

## Platine bestücken

Beim Bestücken der Platine gibt es eine Reihenfolge, welche einzuhalten äußerst ratsam ist.
Die Bauteile werden immer von flach (z.B. Drahtbrücken, Widerstände, …)
nach hoch (z.B. Schalter, Kondensatoren, …) sortiert.
Als vorletztes werden Anschluss-Leitungen verlötet,
da diese ansonsten während dem Bestücken und Löten stören können.
Der optische Maussensor/Prozessor wird ganz zum Schluss bestückt.

> :warning: Immer erst ein Bein eines Bauteiles verlöten
> und dann den korrekten Sitz kontrollieren
> (z.B.: liegen die Bauteile/Drähte sauber auf der Platine auf?).

### Schlechtes Beispiel

<img src="image/pcb-9-bad-example.png" alt="" width="500">
\includegraphics[width=500pt]{image/pcb-9-bad-example.png}

### Drahtbrücken bestücken

<img src="image/pcb-10-jumpers.png" alt="" width="500">
\includegraphics[width=500pt]{image/pcb-10-jumpers.png}

### Kondensatoren und LED bestücken

<img src="image/pcb-11-capacitors-and-leds.png" alt="" width="500">
\includegraphics[width=500pt]{image/pcb-11-capacitors-and-leds.png}

### Taster bestücken

<img src="image/pcb-12-switch-keys.png" alt="" width="500">
\includegraphics[width=500pt]{image/pcb-12-switch-keys.png}

### Elko bestücken

<img src="image/pcb-13-electrolytic-capacitor.png" alt="" height="500">
\includegraphics[width=500pt]{image/pcb-13-electrolytic-capacitor.png}

### Drehgeber bestücken

<img src="image/pcb-14-rotary-encoder.png" alt="" height="500">
\includegraphics[width=500pt]{image/pcb-14-rotary-encoder.png}

### USB Kabel

1. Die Kabelisolation ca. 25mm vom Ende her (Hülle)
   mit einem nicht zu scharfen Messer vorsichtig einkerben.

   <img src="image/usb-1-1.png" alt="" height="150">
   \includegraphics[width=0.2\textwidth]{image/usb-1-1.png}

2. Die Kabelisolation (Hülle) vorsichtig (mit dem Daumennagel) abziehen.

   | | |
   | --- | ------ |
   | ![Isolation 1](image/usb-1-2-1.png) | ![Isolation 2](image/usb-1-2-2.png) |

3. Die Drahtschirmung vorsichtig abwickeln
   (die feinen Drähte können stechen wie Nadeln).

   <img src="image/usb-1-3.png" alt="" height="150">
   \includegraphics[width=0.2\textwidth]{image/usb-1-3.png}

4. Drahtschirm verdrillen und den Folienschirm abwickeln.

   <img src="image/usb-1-4.png" alt="" height="150">
   \includegraphics[width=0.2\textwidth]{image/usb-1-4.png}

5. Die Füllfäden mit einem Messer oder Seitenschneider abschneiden.

   <img src="image/usb-2-5.png" alt="" height="150">
   \includegraphics[width=150pt]{image/usb-2-5.png}

6. Das Ende des verdrillten Schirmgeflechtes verzinnen.

   <img src="image/usb-2-6.png" alt="" height="150">
   \includegraphics[width=150pt]{image/usb-2-6.png}

7. Die Isolation der farbigen Adern an den Enden vorsichtig maximal 3mm entfernen.

   <img src="image/usb-2-7.png" alt="" height="150">
   \includegraphics[width=150pt]{image/usb-2-7.png}

8. Die Adern-Enden verzinnen.
   Die Isolation zieht sich durch die Hitze noch weiter zurück.

   <img src="image/usb-2-8.png" alt="" height="150">
   \includegraphics[width=150pt]{image/usb-2-8.png}

9. Nun kann das USB Kabel in die Platine eingelötet werden.

   <img src="image/pcb-17-usb-cable.png" alt="" height="150">
   \includegraphics[width=150pt]{image/pcb-17-usb-cable.png}

Eine gute Lötstelle zeichnet sich durch eine glänzende Oberfläche aus
(mit bleihaltigem Lötzinn).
Bleifreies Lötzinn ergibt immer eine matte Oberfläche:

<img src="image/pcb-18-bad-example-2.png" alt="" height="500">
\includegraphics[width=500pt]{image/pcb-18-bad-example-2.png}

### Sensor bestücken

<img src="image/pcb-19-processor-sensor.png" alt="" height="500">
\includegraphics[width=500pt]{image/pcb-19-processor-sensor.png}

> :warning: Um Schäden des Sensors durch elektrische Ladungen zu verhindern,
> sollte man sich vor dem Berühren des Sensors selbst entladen haben,
> z.B. an der Erdung der Steckdose oder dem Metall eines Heizkörpers.

## Unterschale bearbeiten für dritte Taste

In der rechten Aufhängung des Scrollrad muss unten das hochstehende Mittelteil entfernt werden, damit das Drücken der dritten Taste funktioniert.

<img src="image/ausbrechen-dritte-taste.png" alt="" height="400">
\includegraphics[width=400pt]{image/ausbrechen-dritte-taste.png}

## Sensor-Folie abziehen

Ziehe nun vorsichtig die Folie vom Sensor (Chip).

<img src="image/Sensor-Folie.png" alt="" height="400">
\includegraphics[width=400pt]{image/Sensor-Folie.png}

## Finaler Zusammenbau

| | |
| --- | ------ |
| 1. | ![Zusammenbau 1](image/zusammenbau-1.png) |
| 2. | ![Zusammenbau 2](image/zusammenbau-2.png) |
| 3. | ![Zusammenbau 3](image/zusammenbau-3.png) |
| 4. | ![Zusammenbau 4](image/zusammenbau-4.png) |

Wenn alles richtig gemacht wurde und keine Kurzschlüsse gelötet wurden,
kann die korrekte Funktion der Maus am PC getestet werden.
Nun haben wir eine 3-Tasten USB-Maus,
welche einmalig auf der Welt ist,
da sie selbst zusammengebaut wurde.
