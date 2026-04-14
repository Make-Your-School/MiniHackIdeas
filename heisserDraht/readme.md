# Heißer Draht - Miniprojekt

## Projektbeschreibung
In diesem Miniprojekt wird ein einfacher Heißer Draht gebaut. Das Ziel des Geschicklichkeitsspiels ist es, eine Metallschlaufe von einem Ende eines gebogenen Drahtes bis zum anderen zu führen, ohne ihn zu berühren. Sobald die Schlaufe den Draht berührt, wird ein Stromkreis geschlossen und ein Summer gibt ein akustisches Signal aus.

## Benötigte Materialien
* 2 Batterien 1,5V (o.ä.)
* Passender Batteriehalter
* Summer (Materialkoffer Nr. 45)
* langer, dicker Metalldraht für die Parkour-Strecke und den Handgriff/Drahtschlaufe
* Pappdeckel o.ä. als Basis/Gehäuse
* Grove Kabel
* Kabel/Litze zum Verbinden der Bauteile
* Lüsterklemme/Wagoklemme oder andere Verbinder
* Klebeband

## Aufbau

![alt Aufbau](aufbau.png)

Quelle: https://www.kreativekiste.de/component/content/article?id=74:heissen-draht-bauen

Bastele aus einem kurzen Stück Draht eine Schlaufe. Damit die Drahtschlaufe besser anzufassen ist, kannst du aus Pappe einen Griff basteln. An der Schlaufe lötest du hinten ein Kabel an.

Biege aus einem langen Stück Draht einen Parkour, welcher zu durchlaufen ist. Du kannst deiner Kreativität freien Lauf lassen. Löte ebenfalls ein Kabel an den Draht an. 
Befestige den Draht-Parkour auf einem Gehäuse (Pappdeckel o.ä.). 
Klebe am Anfang und am Ende des Drahtes 1-2cm mit Klebeband ab. Dadurch markieren wir Start und Ziel. 

Verkabelung: Du Kannst für die Verkabelung eine Lüsterklemme oder Wagoklemme nutzen und ggf. Jumper-Kabel.
* Pluspol Batteriehalter  --> Kabel am heißen Draht
* Minuspol Batteriehalter --> GND-Pin (Schwarz) des Summers
* Kabel der Drahtschlaufe --> Vin-Pin (Rot) und Signal-Pin (Gelb) des Summers

Batterien einlegen und fertig! 

Du kannst natürlich jederzeit die Schwierigkeit deines Parcours erhöhen, indem du den heißen Draht anders formst.

## Erweiterungen
* LED: Für laute Umgebungen ist eine LED gut, welche gleichzeitig zu dem Summer reagiert. Hierfür brauchst du nur eine LED mit passendem Vorwiderstand. Das kurze Beinchen kommt an Batterie-Minus. Das lange Beinchen mit Vorwiderstand wird an die Drahtschlaufe angeschlossen. 
* Ein-/Ausschalter
* Bewegte Hindernisse: Du kannst bspw. rotierende Hindernisse hinzufügen, welche über einen Motor angetrieben werden (s. Link zur Kreativkiste)
* Stoppuhr + Fehlerzähler: Du kannst den Hack auch über einen Microcontroller realisieren. Dann lassen sich automatisch Fehler mitzählen und die Zeit stoppen. Das erhöht den Aufwand und die Kosten aber deutlich.
