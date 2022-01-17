# Deutsches Windows-PC-Tastaturlayout für macOS

Dieses Repository enthält ein deutsches Windows-PC-Tastaturlayout für macOS.

Windows-PC-Tastaturlayout bedeutet in diesem Fall, dass die Sonderzeichen (z.B. `{` oder `]`) an der gleichen Stelle liegen wie auf einer Windows-PC-Tastatur.

## Sonderzeichen

Unterstützte Sonderzeichen bei gedrückter `Alt`-Taste:

![Tastatur-Layout bei gedrückter Alt-Taste](images/keyboard-alt.png)

## Dead-Keys

Die Zeichen <kbd>^</kbd>, <kbd>\`</kbd> und <kbd>´</kbd> sind Dead-Keys.

Das Zeichen <kbd>~</kbd> ist kein Dead-Key.

## Installation

Das `.dmg`-Image herunterladen (siehe Releases) und Anweisungen folgen.

Alternativ: Dieses Repository clonen und das Bundle `pc-win-de-keyboard.bundle` nach `/Library/Keyboard Layouts` kopieren.

## Aktivieren

Das Layout wird über die **Systemeinstellungen** -> **Tastatur** -> **Eingabequellen** aktiviert. Hier auf das `+` unten links klicken.

![Tastaturlayout hinzufügen](images/add-keyboard-layout1.png)

Dann die Sprache **Deutsch** und hier das Layout **PC-Windows Deutsch** auswählen.

![Tastaturlayout auswählen](images/add-keyboard-layout2.png)

Das bisherigen Layout kann man dann per `-` Knopf entfernen (um versehentliches Zurückwechseln zum bisherigen Layout zu verhindern.) Eventuell muss der Mac neugestartet werden, damit das geht.

## Bearbeiten des Layouts

Das Layout bearbeitet man am besten mit dem Tool [Ukulele](http://scripts.sil.org/ukelele).

Das `.dmg`-Image zum Verteilen erstellt man in Ukulele über das Menü: File -> Install -> Export Installer Disk Image...
