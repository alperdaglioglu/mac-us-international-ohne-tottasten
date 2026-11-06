# US International ohne Tottasten (macOS)

Ein macOS-Tastaturlayout für **ANSI-Tastaturen**, das sich wie das Windows-Layout **„US-International“** verhält, aber **ohne Tottasten**.
Die Option-Taste (links und rechts) übernimmt die Rolle von AltGr.

Gedacht für alle, die von Windows auf den Mac wechseln und deutsche Umlaute weiter wie gewohnt tippen möchten.

## Belegung

| Taste | Option | Shift + Option |
|---|---|---|
| `y` | ü | Ü |
| `q` | ä | Ä |
| `p` | ö | Ö |
| `s` | ß | § |
| `5` | € | |
| `e` | é | É |
| `a` | á | Á |
| `n` | ñ | Ñ |
| `,` | ç | Ç |

Die übrigen Option-Belegungen folgen dem AltGr-Layer von Windows US-International. Wo Windows nichts vorsieht, gilt die normale Mac-Belegung (z. B. Option + `g` = ©, Shift + Option + `2` = €).

`'` `"` `` ` `` `~` `^` werden **sofort** ausgegeben, es gibt keine Tottasten.

## Installation

1. Die Datei `US International ohne Tottasten.keylayout` herunterladen.
2. Im Finder <kbd>⇧</kbd><kbd>⌘</kbd><kbd>G</kbd> drücken und `~/Library/Keyboard Layouts` öffnen. Fehlt der Ordner, ihn mit genau diesem Namen in `~/Library` anlegen.
3. Die Datei in diesen Ordner kopieren und sich einmal ab- und wieder anmelden.
4. **Systemeinstellungen → Tastatur → Texteingabe → Bearbeiten → „+“ → Andere** und „US International ohne Tottasten“ hinzufügen.

## Anpassen

Das Layout wird von `generate_keylayout.py` erzeugt. Belegung in der Tabelle `K` ändern und neu erzeugen:

```sh
python3 generate_keylayout.py
```

## Lizenz

MIT, siehe [LICENSE](LICENSE).
