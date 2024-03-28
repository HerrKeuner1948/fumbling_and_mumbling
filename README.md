# Zählen
Als Zählen kann man die Inkrementierung einer Zahl um 1 verstehen. Es handelt sich dabei also um eine Operation auf eine Zahl, auch als unitäre Operation bezeichnet.
# Stellwertsystem
Stellwertsysteme werden verwendet, um eine Zahl darzustellen. Dabei werden Koeffizienten *a<sub>i</sub>* und eine Basis *b* verwendet. Die Koeffizienten nehmen ganzzahlige Werte im Intervall [0,b) an. Für das Dezimalsystem haben wir also die Basis *b* = 10 und die möglichen Werte 0,1,2,3,4,5,6,7,8 und 9 für die Koeffizienten *a<sub>i</sub>*.
Stellwertsysteme stellen also keine Operation dar. Sie verändern nicht die Zahl, nur ihre Darstellung. Zählen ist z.B. unabhängig vom Stellwertsystem
## Nutzen von Stellwertsystemen
Stellwertsysteme sind nützlich, weil sie die Notation von und Operationen auf Zahlen vereinfachen. 
### Notation
Die Notation in Stellwertsystem ist bei geeigneter Basis knapp und bei jeder Basis klar strukturiert.
Man muss sich nur einen kleinen Satz an Symbolen merken und kann so jede beliebige Zahl darstellen.
Niedrige Basen: wenige Ziffern, lange Ziffernketten für große Zahlen
Hohe Basen: viele Ziffern, kurze Ziffernketten für große Zahlen
### (Basis-)Operationen
Man muss sich nur auf einen verkleinerten Ausschnitt der Ganzzahlen konzentrieren. Im Falle vom Dezimalsystem (Basis *b* = 10) ist das der Zahlenraum bis 100. Eigentlich sogar nur bis 89. Grund: Die Koeffizienten *a<sub>i</sub>* können maximal 9 sein. Bei der Multiplikation zweier Zahlen kann also bestenfalls 9*9 = 81 als Einzelergebnis auftauchen. Durch Übertrag (welche maximal 8 sein kann), kann man dann bei 89 landen.
Alle Operationen können auch sehr mechanisch nacheinander durchgeführt werden. Nur im relevanten Zahlenraum müssen die Einzelergebnisse bekannt sein (Rechnen ist faktisch nur auswendiges Wissen von Einzelergebnissen)
## Basis 10
Warum verwenden wir im Allgemeinen die Basis 10? Keine Ahnung. Sehr wahrscheinlich historisch bedingt.
## Sinnvolle Basen
In der Programmierung haben sich das Binär, Oktal- und Hexadezimalsystem durchgesetzt (Mit den Basen 2,8 und 16). Grund ist hier, dass die Hardwarearchitektur dies mehr oder weniger vorgibt.
Wir nutzen im Alltag die Basis 10, also das Dezimalsystem.
Faktisch wäre aber z.B. das Duodezimalsystem wesentlich sinnvoller. Man kann dort leichter erkennen, ob Zahlen vielfache von anderen Zahlen sind. Und das hilft gerade beim Aufteilen ungemein. 
Beispiel: Ein Kreis hat 360°, weil man 360 in sehr viele gleichgroße Faktoren zerlegen kann. Anders gesagt: es ist eine hochzusammengesetzte Zahl (so etwas wie das Gegenteil einer Primzahl).
Anderes Beispiel: Im Babylon nutzte man 60 als Basis. Dies war vermutlich auch das erste verwendete Stellwertsystem.
Ein Kompromiss zwischen hohem Nutzen und handhabbarer Anzahl an Ziffern wäre hierbei das Duodezimalsystem. Werden wir es einführen? Ganz sicher nicht. Zu viel Texte wurden mit dem Dezimalsystem geschrieben. Der Aufwand rechtfertigt nicht den Nutzen. Vor allem weil heute eh niemand mehr rechnet. Und wenn, dann mit Taschenrechner.