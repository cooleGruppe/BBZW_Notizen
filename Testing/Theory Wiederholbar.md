# Wozu Tests
- Fehler vermeiden
- Neue Features testen
- Bestehendes bleibt bestehen
- Gemeldete Fehler
- Bekannt machen einer Lib/Schnittstelle

## Fehler vermeiden
Neuer Code und bestehender Code kann direkt auf Fehler getestet werden
Anforderungen der Software werden direkt gelistet.

## Neue Features testen
Neu erstellter Code korrekt
TDD(Test driven development)

## Bestehendes bleibt korrekt
- Regression
- Keine Sideeffects
- Umfang
- Gesamte Anwendung
- Bedeutende Teile
- Potentiell von Änderungen betroffen
- Während Entwicklung
- Spätestens vor Auslieferung

## Gemeldete Fehler
- Man kann Fehler erneut testen
- Fehler welche vom Kunden gemeldet wurden
- TDD für Fehler
- Umfang
- Spezifisch gemeldete Fehler
- Keine neue Funktionalität
- Zeitpunkt
- Nach Fehlerbehebung
- Vor Auslieferung

## Bekannt machen
- Bibliotheken werden getestet und vertraut machen.

# Testarten

## Wiederholbare Tests
- Wofür
- Merkmale
### Wofür
- benötigt kleiner Aufwand
- Sind reproduzierbar
- Dient als Dokumentation
- Beweis, es funktioniert
- Funktioniert es unter gewissen Bedienungen wie null Werte?
- App wird besser skalierbar
- Automatisierbar

### Merkmale
- Definierte Testdaten
- Testumgebung muss nicht zurückgesetzt werden
- Wartbar
- Isoliert, immer nur eine Komponente
- Keine Daten bleiben übrig nach Test
- Stabil bei verschiedenen Bediengungen
- Resultat immer bestimmt
- Kann automatisiert werden

## Automatisch / Manuell
- Mensch oder Tool?
- Geschwindigkeit
- Wiederhollbarkeit
- Exaktheit

### Automatisch

- Mit Tools wie XUnit
- Schnell
- Wiederholbar
- Exakt
- Hoher Startaufwand

### Manuell
- Von Mensch
- Langsam
- Einzigartig
- Flüchtigkeitsfehler
- Regelmässige Durchführung teuer

## Prinzipen
- Vollständig
- Regression
- Vergleich
- Sicherheit
- Früh
- Realistisch
- Reproduzierbar