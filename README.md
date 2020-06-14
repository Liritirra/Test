# LaTeX Klasse: Protokoll
`Alpha: 1.00`

[Changelog](CHANGELOG.md)

[Dokumentation](Dokumentation_Klasse_Protokoll.pdf)

---

Dieses Template stellt die LaTeX Klasse 'Protokoll' zur Verfügung.
Diese stellt eine große Zahl an nützlichen [Paketen](#Pakete) für ein Protokoll im naturwissenschaftlichen Rahmen zur Verfügung. Zusätzlich werden diese Pakete direkt richtig konfiguriert.

Darüber hinaus stellt das Paket eine große Zahl an nützlichen Befehlen zur Verfügung.

Über die Pakete im Ordner *Styles* werden vordefinierte [Stile](#Stile) angeboten.

---
#### Pakete

Paket | Seit&nbsp;Version | Nutzen
--- | --- | ---
nag | `Alpha: 1.00` | Old habits die hard. Warnt vor veralteten Befehlen.
etoolbox | `Alpha: 1.00` | Bietet Alternative Wege für LaTeX Kernel Befehle an.
xkeyval | `Alpha: 1.00` | Bietet ein Key/Value System für Paket/Klassen Optionen an.
KOMA-Script | `Alpha: 1.00` | Umfangreiches Paket, stellt die Grundklasse zur Verfügung.
inputenc | `Alpha: 1.00` | Ermöglicht verschiedene Codierungen für den Quellcode. (Hier *UTF-8*)
fontenc | `Alpha: 1.00` | Ermöglicht verschiedene Codierung im erstellten PDF.
lmodern | `Alpha: 1.00` | Stellt die Schriftart *Latin Modern* zur Verfügung. Erhöht die Schriftauflösung.
import | `Alpha: 1.00` | Ermöglicht eine verbesserte Importierung von externen Datein.
micotype | `Alpha: 1.00` | Verbessert mikrotypografische Einstellungen.
blindtext | `Alpha: 1.00` | Ermöglicht Platzhaltertexte.
everypage | `Alpha: 1.00` | Stellt einen Hook für jeden Seitenbeginn zur Verfügung.
abstract | `Alpha: 1.00` | Stellt eine *abstract* Umgebung zur Verfügung.
environ | `Alpha: 1.00` | Erleichtert und verbessert Erstellung von Umgebungen.
chngcntr | `Alpha: 1.00` | Lässt Counter bei Hooks zurücksetzen (z.B. jede Section).
babel | `Alpha: 1.00` | Übersetzt Vieles. (Hier: *Deutsch*)
geometry | `Alpha: 1.00` | Ermöglicht Papier und Dokumenteneinstellung.
pdflscape | `Alpha: 1.00` | Ermöglicht Querformat.
caption | `Alpha: 1.00` | Captions können präzise angepasst werden.
scrlayer-scrpage | `Alpha: 1.00` | Erweiterungspacket von KOMA-Script, ermöglicht Anpassung von Headern und Footern.
tocbasic | `Alpha: 1.00` | Ermöglicht Anpassungen des TOC.
tabto | `Alpha: 1.00` | Stellt einen Ersatz für Tab zur Verfügung.
enumitem | `Alpha: 1.00` | Ermöglicht die präzise Erstellung von Aufzählungen.
multicol | `Alpha: 1.00` | Ermöglicht mehrspaltige Dokumente. Schließt auf der letzten Seite der Umgebung alle Spalten auf der gleichen Höhe ab.
graphicx | `Alpha: 1.00` | Einbindung von Grafiken.
wrapfig | `Alpha: 1.00` | Ermöglicht Floats von Text umfließen zu lassen.
pgfplots | `Alpha: 1.00` | Ermöglicht Darstellung von Plots aus externen/internen Dateien.
TikZ | `Alpha: 1.00` | *Teil von pfgplots* Ermöglicht das Programmieren von Vektorgrafiken.
float | `Alpha: 1.00` | Verbessert Floats. Ermöglicht präzise Positionierung.
svg | `Alpha: 1.00` | Ermöglicht die Einbindung von SVGs.
tcolorbox | `Alpha: 1.00` | Ermöglicht Farbboxen
subcaption | `Alpha: 1.00` | Ermöglicht Floats in Floats mit eigenen Captions
amsfonts | `Alpha: 1.00` | Schriften für Mathematikumgebung
amsmath | `Alpha: 1.00` | Schriften für Mathematikumgebung
amssymb | `Alpha: 1.00` | Schriften für Mathematikumgebung
sansmathfonts | `Alpha: 1.00` | Schriften für Mathematikumgebung
cancel | `Alpha: 1.00` | Ermöglicht (durch)streichen
cases | `Alpha: 1.00` | Ermöglicht Mathematische Fälle
nicefrac | `Alpha: 1.00` | Ermöglicht Querbrüche
autobreak | `Alpha: 1.00` | Formeln im Align werden umgebrochen
gauss | `Alpha: 1.00` | Ermöglicht Gaussche Eliminierung
siunitx | `Alpha: 1.00` | Darstellung von Einheiten und Potenzen
mhchem | `Alpha: 1.00` | Chemiepacket, großer Umfang (\\ce)
chemmacros | `Alpha: 1.00` | Chemiepacket, großer Umfang (\\ch)
chemformula | `Alpha: 1.00` | *Teil von chemmacros* Chemiepacket (\\ch)
ghsystem | `Alpha: 1.00` | *Teil von chemmacros* Chemiepacket
chemfig | `Alpha: 1.00` | Zeichnen von chemischen Strukturen
textgreek | `Alpha: 1.00` | Ermöglicht grichische Zeichen auch ohne Matheumgebung
listings | `Alpha: 1.00` | Ermöglicht schöne Darstellung von Programmiercodes
physics | `Alpha: 1.00` | Viele kleine nützliche Mathematische Ausdrücke
natbib | `Alpha: 1.00` | Erzeugt Literaturverzeichnis aus bib Datei
babelbib | `Alpha: 1.00` | Stellt Packete für Deutsches Literaturverzeichnis zur Verfügung
url | `Alpha: 1.00` | Ermöglicht Links
hyperref | `Alpha: 1.00` | Erlaubt Referenzierung und Anpassung dieser innerhalb des Dokumentes. Metadaten des Dokuments können angepasst werden.
cleveref | `Alpha: 1.00` | Verbessert Referenzierung
hypcap | `Alpha: 1.00` | Korrigiert Anker zu Floats
imakeidx | `Alpha: 1.00` | Ermöglicht Index
tablefootnote | `Alpha: 1.00` | Ermöglicht footnotes aus Table Floats
acronym | `Alpha: 1.00` | Stellt Abkürzungen und deren Verzeichnis zur Verfügung
lastpage | `Alpha: 1.00` | Hook zur letzen Seite
tabularx | `Alpha: 1.00` | Tabellen deren Breite definierbar ist
tabu | `Alpha: 1.00` | Vielseitiges Tabellenpaket
tabulary | `Alpha: 1.00` | Tabellen deren Höhe definierbar ist
array | `Alpha: 1.00` | Anpassungen von Tabellenzellen und Textpositionierung in diesen
booktabs | `Alpha: 1.00` | Tabellenrahmengestalltung
longtable | `Alpha: 1.00` | Tabellen die über mehrere Seiten gehen können
multirow | `Alpha: 1.00` | Übergreifende Zellen
pgfplotstable | `Alpha: 1.00` | Erzeugt Tabellen aus externen Dateien
xcolor | `Alpha: 1.00` | Ermöglicht farbige Texte und Boxen
changes | `Alpha: 1.00` | Ermöglicht Kommentare
qrcode | `Alpha: 1.00` | Stellt QRCodes zur Verfügung


---
#### Stile

Stil | <nobr>Seit Version</nobr> | Nutzen
--- | --- | ---
HHU_Default | `Alpha: 1.00` | Protokoll für die Heinrich-Heine-Universität
