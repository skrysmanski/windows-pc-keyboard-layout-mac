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

Alternativ: Dieses Repository clonen und das Bundle `pc-win-de-keyboard.bundle` nach `/Library/Keyboard Layouts` kopieren. (Tipp: Im Finder `Cmd+Shift+G`.)

## Aktivieren

Das Layout wird über die **Systemeinstellungen** -> **Tastatur** -> **Eingabequellen** aktiviert. Hier auf das `+` unten links klicken.

![Tastaturlayout hinzufügen](images/add-keyboard-layout1.png)

Dann die Sprache **Deutsch** und hier das Layout **Deutsch - PC** auswählen.

![Tastaturlayout auswählen](images/add-keyboard-layout2.png)

Das bisherigen Layout kann man dann per `-` Knopf entfernen (um versehentliches Zurückwechseln zum bisherigen Layout zu verhindern.) Siehe aber auch den nächsten Abschnitt.

## Tastaturlayout im Anmeldebildschirm

Leider können im Anmelde-/Sperrbildschirm keine eigenen Tastaturlayouts verwendet werden. (Hier funktionieren nur die, die mit macOS ausgeliefert werden.)

Sofern als [Systemsprache](https://support.apple.com/de-de/HT202036) Deutsch verwendet wird, wird im Anmeldebildschirm einfach das Tastaturlayout "Deutsch" verwendet. (Ist auf dem Mac nur ein Benutzer vorhanden, entspricht die Systemsprache immer automatisch der Benutzersprache.)

Ist die Systemsprache eine andere (z.B. Englisch), dann gilt:

* Ist beim Benutzer das Tastaturlayout "Deutsch" in den Eingabequellen hinterlegt (muss *nicht* aktiv sein), wird "Deutsch" als Tastaturlayout im Anmeldebildschirm verwendet.
* Ansonsten wird ein englisches Tastaturlayout (US oder Britisch) verwendet.

Das bedeutet: Ist die Systemsprache Englisch, darf das von macOS mitgelieferte Tastaturlayout "Deutsch" *nicht* entfernt werden!

## Bearbeiten des Layouts

Das Layout bearbeitet man am besten mit dem Tool [Ukulele](https://software.sil.org/ukelele/).

Das `.dmg`-Image zum Verteilen erstellt man in Ukulele über das Menü: File -> Install -> Export Installer Disk Image...
