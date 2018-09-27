# vollmachten_muster
# Allgemeine Dateien zur Erzeugung von Vollmachten 

Um betreuungsrechtliche Vorsorge zu treffen, benötigt man im wesentlichen folgende Dokumkente:

- Vorsorgevollmacht,
- Patientenverfügung.

Bei Familien sind das für jede Dokumentenart mindestens drei. Bei Bevollmächtigung mehrerer
Personen gar noch mehr.

Deshalb habe ich versucht, mit ein wenig Standardisierung den Aufwand etwas zu reduzieren.

Dazu habe ich insbesondere die Personendaten in separate Dateien gezogen.

Vorlage waren die Dokumente des [Justizministeriums](https://www.bmjv.de). Dort finden sich
ausführliche Beschreibungen und Beispieldokumente im Bereich 
[Themen - Vorsorge und Patientenrechte](https://www.bmjv.de/DE/Themen/VorsorgeUndPatientenrechte/VorsorgeUndPatientenrechte_node.html).

Trotzdem bin ich in vielen Punkten davon abgewichen.

## Mechanik der Dokumentenerzeugung

Die Hauptdokumente in LaTeX sind vorsorgevollmacht.tex und patverf.tex (jeweils mit Prä- und Postfix im Dateinamen).

Diese verwenden diverse Hilfsdateien (z.B. cmd.tex). Individuell davon ist eine (cmd_nameinitials.tex). In dieser werden 
die Personendaten erfasst (cmd_sample.tex ist das Beispiel). 



tbc
