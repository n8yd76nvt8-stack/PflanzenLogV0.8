# Pflanzenlog v0.8 – Kurzanleitung

## Zweck und Speicherung
Pflanzenlog dokumentiert Gießvorgänge, Intervalle, Notizen und Zusätze. Die Daten liegen lokal im Browser auf dem jeweiligen Gerät; es gibt keine automatische Synchronisierung.

## Gießvorgang erfassen
1. Wähle eine oder mehrere Pflanzen aus. Für jede Pflanze wird die Wassermenge in Litern separat erfasst.
2. Das Intervall bis zum nächsten Gießen wird in ganzen Tagen angegeben. Bei genau einer ausgewählten Pflanze wird das zuletzt für diese Pflanze gespeicherte Intervall automatisch übernommen, sofern ein früherer Eintrag existiert. Bei Mehrfachauswahl wird das Intervall nicht automatisch überschrieben.
3. Das Gießdatum ist standardmäßig auf heute gesetzt und **„Jetzt“** ist aktiviert. Dann speichert die App die aktuelle lokale Uhrzeit als Gießzeit.
4. Bei einem rückwirkenden Datum wird „Jetzt“ automatisch deaktiviert. Wähle dann die tatsächliche Gießuhrzeit aus. Auch wenn du „Jetzt“ für das heutige Datum manuell abwählst, musst du eine Uhrzeit angeben.
5. Wähle die Zusätze und trage die Dosierung ein, sofern du Zusätze verwendest.
6. Unter **Optionale Parameter: Klarwasser, Zwischenguss, pH & EC** kannst du bei Bedarf **Klarwasser** oder **Zwischenguss** markieren sowie pH-Wert (0–14) und EC in µS/cm erfassen. Der Bereich ist standardmäßig eingeklappt.
7. Ein **Zwischenguss** wird protokolliert, verschiebt aber die nächste Fälligkeit nicht. Die zuletzt bei einem regulären Gießen verwendete Menge bleibt als Standardmenge erhalten.
8. Ergänze bei Bedarf eine Notiz und speichere den Vorgang.

Bei mehreren Pflanzen werden einzelne Pflanzeneinträge mit einer gemeinsamen Ereignis-ID gespeichert

## Zusätze und Produktkatalog
Öffne den Bereich **Zusatz-Katalog**, um Produkte anzulegen, zu bearbeiten, zu sortieren, zu importieren oder zu exportieren. Die Sortierung der Produktliste gilt auch für die Zusatzauswahl oben.

## Historie und nächste Gießtermine
Oben zeigt die App den nächsten Gießtermin pro Pflanze. Die Historie zeigt standardmäßig höchstens sechs passende Einträge; ältere Einträge bleiben gespeichert und werden weiterhin exportiert. Einträge können einzeln gelöscht werden.

## Datensicherung und Export
- **Sicherung herunterladen** erstellt eine JSON-Sicherung der Pflanzen, Einträge, Zusätze und Einstellungen.
- **Sicherung importieren** ersetzt nach Bestätigung die aktuellen lokalen Daten.
- **Gießprotokoll CSV** exportiert Gießereignisse
- **Zusätze CSV** exportiert verwendete Zusätze und Dosierungen
- **Produktkatalog CSV exportieren/importieren** dient zum Übertragen des Katalogs zwischen Geräten; der Import zeigt zunächst eine Vorschau.

## Werkseinstellungen
Ganz unten kann über **„Auf Werkseinstellungen zurücksetzen“** der lokale Bestand dieser App auf dem Gerät gelöscht werden. Vorher erscheint eine Sicherheitsabfrage. Der Vorgang kann nicht rückgängig gemacht werden; exportiere bei Bedarf vorher eine JSON-Sicherung.

## Hinweise
- Regelmäßig Backups erstellen; der Browser-Speicher ist kein Ersatz dafür.
- Für Offline-Nutzung die veröffentlichte HTTPS-App zunächst einmal online öffnen.
