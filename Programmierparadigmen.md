**Programmierparadigmen**

**Design Patterns:** Singleton, Observer, and Factory
Design Patterns sind wiederverwendbare Lösungen für häufig auftretende Probleme in der Softwareentwicklung. 
Hier sind drei wichtige Entwurfsmuster: Singleton, Observer und Factory.

**Singleton Pattern**
Zweck:
Das Singleton-Pattern stellt sicher, dass eine Klasse genau eine Instanz hat und bietet einen globalen Zugriffspunkt auf diese Instanz.

**Anwendung:**
Es wird verwendet, wenn genau ein Objekt einer Klasse benötigt wird, um eine Aktion zu koordinieren.

**Beispiel in Python:**
class Singleton:
    _instance = None

    def __new__(cls):
        if cls._instance is None:
            cls._instance = super(Singleton, cls).__new__(cls)
        return cls._instance


Deklaratives Programmierung

Deklaratives Programmieren ist ein Programmierparadigma, bei dem der Fokus darauf liegt, was das Programm tun soll, anstatt wie es das tun soll. 
Es beschreibt das Ziel oder die gewünschten Ergebnisse, ohne die genauen Schritte zur Erreichung dieses Ziels zu spezifizieren.
Beispiele für deklarative Programmieransätze sind SQL für Datenbankabfragen und funktionale Programmierung wie Haskell.


Prozeduale Programmierung

Prozedurale Programmierung ist ein Stil des imperativen Programmierens, bei dem der Code in Prozeduren oder Funktionen organisiert ist.
Diese Prozeduren kapseln spezifische Aufgaben oder Berechnungen und können wiederverwendet werden. Ein Beispiel für eine prozedurale Sprache ist C.​

