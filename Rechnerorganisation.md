**Rechnerorganisation**

**Konvertierung vom Zahlensystem**
Heute habe ich wiederholt, wie das Konvertieren von Dezimalzahlen in das Binärsystem und vom Binärsystem ins Hexadezimalsystem funktioniert.
Dezimalzahlen ins Binärsystem: Beim Berechnen von Dezimalzahlen in Binärzahlen dividiert man die Dezimal fortlaufend durch 2. Wenn aus der Zahl die man durch 2 dividiert eine Kommazahl rauskommt, bzw. die Zahl einen Rest hat, dann schreibt man einen Rest an. Beispiel: 28:2= 14 0 Rest, 14:2=7 0 Rest, 7:2=3 1 Rest, 3:2=1 1 Rest, 1:2= 0 1 Rest. Dann nimmt man die Rest in umgekehrter Reihenfolge, also von unten nach oben und man hat seine Dezimalzahl in Binär konvertiert. 28 = 11100

**Binärzahlen ins Hexadezimalsystem**
Beispiel: 00100010 11000100 11010001 01011010
Zuerst werden die Ziffern zu Viererblöcke gruppiert. Man beginnt dabei bei der kleinsten Stelle von rechts. Jede Gruppe wird dann separat in eine entsprechende Hexadezimalzahl umgewandelt. Eine Hexadezimalzahl reicht von 0 bis F (0-15), wobei F für die Dezimalzahl 15 steht. Die Zuordnung erfolgt wie folgt: 0000 für 0, 0001 für 1, ..., 1010 für A, 1011 für B, ..., 1111 für F.


**Operatoren**
Was ist ein Opreator? Operatoren sind Symbole die in der Programmierung und in der Mathematik benutzt werden, um Operationen wie Addition, Multiplikation, Subtraktion und Division durchzuführen. Ein unärer Operator benötigt einen Operator, ein binärer Operator braucht zwei Operatoren und ein ternärer Operator benötigt 3 Operatoren.

**Relationale Operatoren:** Relationale Operatorenvergleichen  zwei Werte miteinander. Das Ergebnis ist immer ein boolescher Wert, also true oder false. Zu den relationalen Operatoren zählen:

==	Das doppelte Gleichheitszeichen überprüft zwei Werte auf ihre Gleichheit, kann jedoch nicht bei Zeichenketten eingesetzt werden.
!=	Das Gleichheitszeichen mit vorgestelltem Ausrufezeichen bedeutet "ungleich". Es überprüft zwei Werte auf Ihre Ungleichheit.
>	Das "Größer"-Zeichen überprüft, ob ein Wert größer ist als der andere.
<	Das "Kleiner"-Zeichen überprüft, ob ein Wert kleiner ist als der andere.
>=	 Das Größer/Gleich-Zeichen überprüft, ob ein Wert größer oder gleich dem anderen ist.
<=	Das Kleiner/Gleich-Zeichen überprüft, ob ein Wert kleiner oder gleich dem anderen ist.


**Logische Operatoren:** Logische Operatoren dienen dazu boolsche Ausdrücke zu vergleichen.
Es gibt folgende Operatoren:

&&	Doppeltes UND ist eine logische UND-Verknüpfung, bei der wir nur ein wahres Ergebnis erhalten, wenn beide Werte wahr sind. Ist an dieser Stelle bereits der erste Operator falsch (false) so wird der zweite Operand nicht mehr ausgewertet, da false und irgendwas bei einer logischen UND-Verknüpfung als Resultat immer false hat.
&	Einfaches UND ist eine logische UND-Verknüpfung. Bei dieser logischen UND-Verknüpfung werden beide Operanden ausgewertet.
||	Doppeltes ODER ist eine logische ODER-Verknüpfung, bei der wir nur ein falsches Ergebnis erhalten, wenn beide Werte falsch sind. Ist an dieser Stelle bereits der erste Operator wahr (true) so wird der zweite Operand nicht mehr ausgewertet, da true und irgendwas bei einer logischen ODER-Verknüpfung als Resultat immer truehat.
|	Einfaches ODER ist eine logische ODER-Verknüpfung. Bei dieser logischen ODER-Verknüpfung werden beide Operanden ausgewertet.
!	Das Ausrufezeichen ist der Negierungsoperator in der booleschen Logik. Aus wahr (true) wird falsch (false) und umgekehrt.
^	Das "Dach" wird als Exklusiv-Oder bezeichnet. Entweder der erste oder der zweite Ausdruck muss wahr sein. Es dürfen aber nicht beide Ausdrücke gleich sein, damit das Ergebnis wahr wird.

Arismethische Operatoren: Die arismethischen Operatoren sind +, -, * und /. (Addieren, Subtrahieren, Multiplizieren und Dividieren)


**Binäraddition:**
Eine Binärzahl besteht nur aus zwei Ziffern, nämlich 0 und 1. Daher gelten bei der Addition von Binärzahlen 4 bestimmte Regeln: Addierst du die Ziffer 0 mit der Ziffer 0, so ist das Ergebnis auch 0 (0 + 0 = 0). Addierst du die Ziffer 0 mit der Ziffer 1 oder umgekehrt, also Ziffer 1 mit der Ziffer 0, so ist das Ergebnis jeweils 1 (0 + 1 = 1 bzw. 1 + 0 = 1). Addierst du die Ziffer 1 mit der Ziffer 1, so ist das Ergebnis wieder 0. Du erhältst jedoch einen so genannten Übertrag von 1, den du bei der nächsten Berechnung berücksichtigen musst (1 + 1 = 0 und Übertrag 1).
Beispiel: 1011 + 0110 = 10001


**Binärsubtraktion**
Die Binärsubtraktion funktioniert ähnlich wie die Dezimalsubtraktion, allerdings basiert sie auf dem Binärsystem, das nur die Zahlen 0 und 1 verwendet. Im Binärsystem gelten die folgenden Regeln für die Subtraktion:

0 - 0 = 0
1 - 0 = 1
1 - 1 = 0
0 - 1 = 1 mit Übertragung von einer höheren Bit-Stelle

Beispiel: 1101- 1011
Von rechts nach links beginnend:
1-1=0, 0-1=1 mit 1 Übertrag, 1- 0= 1, 1-1=0

Das Ergebnis ist 0110.

Das Ergebnis im Binärsystem ist das Ergebnis immer positiv, da das Binärsystem keine negativen Zahlen direkt darstellen kann. Wenn das Subtrahend größer als der Minuend ist, wird das Ergebnis negativ. In solchen Fällen kann man das Zweierkomplement verwenden, um die Subtraktion als Addition darzustellen.




