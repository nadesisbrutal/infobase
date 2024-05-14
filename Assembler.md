**Fachbegriffe**

**High-Level-Programmiersprache:** Eine Programmiersprache, die menschenlesbar ist und auf einem höheren Abstraktionsniveau arbeitet. 
Diese Sprachen sind näher an natürlicher Sprache und ermöglichen Entwicklern, komplexe Aufgaben mit weniger Code zu erledigen. Beispiel: Python, Java, C++.

**Assembly-Sprache:** Eine low-level Programmiersprache, die eng mit der Architektur der zugrunde liegenden Hardware verbunden ist. 
Sie verwendet Befehle, die direkt von der CPU ausgeführt werden können, und besteht aus kurzen, abkürzenden Befehlen, die in maschinenlesbarer Form vorliegen. Beispiel: x86 Assembly.

**Machine Language:** Die niedrigste Ebene der Programmiersprachen, die direkt von der CPU verstanden wird. 
Es besteht aus einer binären Darstellung von Befehlen, die von der Hardware ausgeführt werden können. Beispiel: Binäre Maschinensprache (0s und 1s).

**Abstraktionsebene:** Die Abstraktionsebene bezieht sich auf die ideale Schnittstelle zwischen verschiedenen Abstraktionsniveaus in einem System.
Jede Ebene bietet eine bestimmte Sicht oder Darstellung der darunter liegenden Details, wodurch komplexe Systeme in leichter verständliche Teile aufgeteilt werden können.

**Abstraktion:** Abstraktion bezieht sich darauf, unnötige Details zu verbergen und nur die relevanten Aspekte zu präsentieren. 
Durch Abstraktion können komplexe Probleme in einfachere Teilprobleme unterteilt werden, was die Entwicklung und Wartung von Software erleichtert.

**Instanzieren:** Instanzieren bezieht sich darauf, eine Klasse in einem objektorientierten Programmierparadigma zu verwenden, um ein konkretes Objekt zu erzeugen. 
Es ist der Prozess, bei dem eine Klasse als Datentyp verwendet wird, um ein Objekt zu erzeugen, das spezifische Eigenschaften und Methoden hat.

**Instanz:** In der objektorientierten Programmierung ist eine Instanz ein konkretes Objekt, das von einer Klasse erstellt wurde. 
Jede Instanz einer Klasse hat ihre eigenen Daten und kann auf die Methoden der Klasse zugreifen.



Die **Neumann-Architektur** ist ein grundlegendes Konzept in der Computertechnik, das die Struktur von modernen Computern beschreibt.
**Control Unit:** Die Steuerungseinheit koordiniert die Abläufe im Rechner. 
Sie interpretiert Befehle aus dem Speicher und steuert die Ausführung von Programmen, indem sie die Ausführung von Befehlen und den Datentransfer zwischen anderen Einheiten des Computers kontrolliert.

**Arithmetic/Logic Unit (ALU):** Die Rechen- und Logikeinheit führt die arithmetischen Operationen (wie Addition und Subtraktion) sowie logische Operationen (wie AND, OR, NOT) durch. 
Sie ist für die eigentliche Verarbeitung von Daten zuständig.

**Memory Unit:** Die Speichereinheit umfasst den Speicher des Computers, in dem Daten und Programme gespeichert werden. 
Dieser Speicher kann sowohl für temporäre Daten während der Ausführung von Programmen als auch für langfristige Speicherung von Programmen und Daten verwendet werden.

**Register und Adressen:** Register sind kleine, schnelle Speicherplätze innerhalb der CPU, die zur temporären Speicherung von Daten und Befehlen verwendet werden.
Adressen sind numerische Werte, die verwendet werden, um auf bestimmte Speicherorte im Speicher zuzugreifen.

Die Webseite **"https://dannyqiu.me/mips-interpreter/"** ist ein MIPS-Assembler-Interpreter. Sie ermöglicht es Benutzern, MIPS-Assembly-Code einzugeben und auszuführen. 
Auf der Webseite kann man Folgendes sehen:

**Eingabefeld:** Hier können Benutzer ihren MIPS-Assembly-Code eingeben.
**Ausgabefeld:** Hier wird der Ausgabe-Maschinencode oder das Ergebnis der Ausführung des eingegebenen MIPS-Codes angezeigt.
**Schaltflächen:** Es gibt Schaltflächen zum Ausführen des eingegebenen Codes, zum Löschen des Inhalts der Eingabe- und Ausgabefelder und zum Herunterladen des generierten Maschinencodes.

**Instruction:** Eine Anweisung oder ein Befehl, der von einem Computer ausgeführt wird, um eine bestimmte Operation durchzuführen.
**Mnemonic:** Ein kurzer, symbolischer Name, der einer bestimmten Maschinenanweisung zugeordnet ist, um sie für den Programmierer leichter lesbar zu machen.
**Instruction Encoding:** Der Prozess, bei dem eine Anweisung in eine maschinenlesbare Form umgewandelt wird, normalerweise eine binäre Darstellung.
**Instruction Format:** Die Struktur oder das Layout einer Maschinenanweisung, einschließlich des OPCode (Operation Code), Operanden und anderen relevanten Feldern.
OPCode: Der Teil einer Maschinenanweisung, der die auszuführende Operation identifiziert.
Register: Ein kleiner Speicherplatz innerhalb der CPU, der für die Speicherung von Daten oder Befehlen während der Ausführung von Programmen verwendet wird.
Memory Address: Eine numerische Adresse, die verwendet wird, um auf einen bestimmten Speicherort im Speicher eines Computers zuzugreifen.

ADDIU $0, $1, 5

Um die MIPS-Instruktion "ADDIU $0, $1, 5" in Hexadezimalcode umzuwandeln, folgen wir diesem Prozess:

OPCode für ADDIU: 001001 (konstant für ADDIU)
Nummer des Quellregisters ($1): 00001 (entspricht $1)
Nummer des Zielregisters ($0): 00000 (entspricht $0)
16-Bit unmittelbarer Wert (5): 0000 0000 0000 0101 (5 in binärer Form)
Der Hexadezimalcode für diese Instruktion ergibt sich, indem wir die Binärwerte in Gruppen von 4 Bits aufteilen und diese in ihre entsprechenden hexadezimalen Ziffern umwandeln:

OPCode: 0010 01 -> 0x2
Nummer des Quellregisters ($1): 0000 1 -> 0x1
Nummer des Zielregisters ($0): 0000 0 -> 0x0
16-Bit unmittelbarer Wert (5): 0000 0000 0000 0101 -> 0x0005
Also lautet der Hexadezimalcode für "ADDIU $0, $1, 5" 0x20100005.


