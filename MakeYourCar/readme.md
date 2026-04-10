# Bauanleitung

Diese Anleitung beschreibt den Aufbau eines einfachen, zweirädrigen Fahrzeugs, das über zwei Motoren gesteuert wird.

---

## Material & Vorbereitung
* **Basis:** Ein Sperrholzbrettchen oder dicke Pappe (9 x 14 cm).
* **Antrieb:** Zwei Getriebemotoren inklusive passender Räder oder Flaschendeckel, Batterien und zwei Taster.
* **Stabilisierung:** Ein Tischtennisball (halbiert) oder ähnliches.
* **Werkzeug:** Heißkleber.

---

## Montage 
1. **Antrieb montieren:** Befestige die beiden Getriebemotoren samt Rädern an einem Ende des Sperrholzbrettchens.
2. **Gleichgewicht herstellen:** Schneide einen Tischtennisball in zwei Hälften. Klebe eine Hälfte mit Heißkleber auf die Unterseite des anderen Brettchen-Endes. Dies sorgt dafür, dass das Fahrzeug waagerecht steht und über den Boden gleiten kann.
3. **Verkabelung:** Das Fahrzeug wird über zwei separate Stromkreise gesteuert. Verbinde jeden Motor über einen eigenen **Taster** mit der Batterie. **Funktionsweise:** Tastendruck: Stromkreis geschlossen (Motor läuft). Loslassen: Stromkreis unterbrochen (Motor steht).

![Illustration von https://mint-unt.de/mobil-mit-calliope/](https://github.com/Make-Your-School/MiniHackIdeas/blob/main/MakeYourCar/Mobil-6.jpg)

---

## Steuerung des Fahrzeugs
Die Lenkung erfolgt über die gezielte Aktivierung der Motoren:

* **Geradeausfahrt:** Beide Taster gleichzeitig drücken.
* **Rechtskurve:** Nur den linken Taster drücken (der linke Motor schiebt das Fahrzeug nach rechts).
* **Linkskurve:** Nur den rechten Taster drücken (der rechte Motor schiebt das Fahrzeug nach links).
* **Stopp:** Beide Taster loslassen.

  ---

## Ausblick: Automatisierung mit Calliope mini
![Illustration von https://mint-unt.de/mobil-mit-calliope/](https://github.com/Make-Your-School/MiniHackIdeas/blob/main/MakeYourCar/Mobil-13.jpg)
1. Verbinde die Motoren mit der Motortreiber-Leiste des Calliope mini. Motor 1: Schließe die Kabel an den Pin **GND** und den Anschluss **A** an. Motor 2: Schließe die Kabel an den Pin **GND** und den Anschluss **B** an.
2. Um den Motoren genügend Kraft zu geben, wird ein 9V-Block als zusätzliche Energiequelle benötigt: Verbinde den **Pluspol** (rotes Kabel) der Batterie mit dem Pin **Vin**. Verbinde den **Minuspol** (schwarzes Kabel) der Batterie mit einem freien **GND**-Pin.
3. Verwende für den Calliope mini die 3V-Batteriebox: Stecke den weißen, verpolungssicheren Stecker der Batteriebox in die vorgesehene Buchse auf dem Calliope. **Hinweis:** Der Stecker passt aufgrund seiner Form nur in einer Richtung – bitte keine Gewalt anwenden.
4. Damit dein Fahrzeug auf Knopfdruck von der Startlinie präzise ins Zielfeld steuert, musst du nun den entsprechenden Code übertragen:
Erstelle das Programm in deinem Editor (z. B. MakeCode oder Open Roberta). Übertrage die Datei per USB auf deinen Calliope. Positioniere das Fahrzeug an der Startlinie und drücke den programmierten Knopf (z. B. Taste A), um die Fahrt zu starten.
    
 ![Illustration von https://mint-unt.de/mobil-mit-calliope/](https://github.com/Make-Your-School/MiniHackIdeas/blob/main/MakeYourCar/makecode-editor9.jpg)
