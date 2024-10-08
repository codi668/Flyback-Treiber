# Flyback Musik-Treiber

Dieses Projekt verwendet einen Flyback-Treiber, um Musiksignale zu erzeugen und diese über Zeilentrafos auszugeben. Der Flyback-Treiber moduliert das Audiosignal und überträgt es an den Zeilentrafo, der die Musik in hörbare Geräusche umwandelt. Dieses Setup eignet sich für experimentelle Audioprojekte oder künstlerische Installationen.

## Funktionsweise

Der Flyback-Treiber empfängt analoge Audiosignale (zum Beispiel von einem Musikplayer oder einem Synthesizer) und nutzt einen Flyback-Transformator, um diese auf Hochspannungsniveau zu übertragen. Der Zeilentrafo empfängt das modulierte Signal und wandelt es in hörbare Schwingungen um, die als Musik oder Geräusche wahrgenommen werden.

## Features

- **Audio-Ausgabe:** Musik wird über Zeilentrafos ausgegeben.
- **Einfache Integration:** Der Treiber lässt sich mit verschiedenen Audioquellen und Verstärkern verbinden.
- **Verstellbare Lautstärke:** Die Lautstärke kann durch Anpassung der Eingangssignale gesteuert werden.
- **Experimentelles Design:** Ideal für künstlerische Projekte oder Sound-Installationen.

## Komponenten

1. **Flyback-Treiber-Modul**: Ein handelsübliches Flyback-Modul, das für die Hochspannungssteuerung verwendet wird.
2. **Zeilentrafo**: Ein Transformator, der zur Erzeugung der hörbaren Töne verwendet wird.
3. **Audioquelle**: Ein Gerät, das über 3,5mm Klinkenanschluss Musik wiedergibt (z. B. Smartphone, Laptop, etc.).
4. **Stromversorgung**: Ein Netzteil, das 12V bis 24V DC liefert (je nach Flyback-Modul).
5. **Kabel**: Zur Verbindung der Audioquelle, des Flyback-Treibers und des Zeilentrafos.

## Installationsanleitung

### Benötigte Materialien

- **Flyback-Treiber-Modul** (z.B. aus einem alten CRT-Monitor oder TV)
- **Zeilentrafo** (aus einem Fernseher oder Monitor)
- **Audioquelle** (mit 3,5mm Klinkenanschluss)
- **Netzteil** (12V-24V DC, abhängig vom Flyback-Modul)
- **Kabel und Stecker** (zur Verbindung der Komponenten)
- **Sicherheitsvorkehrungen** (Isoliermaterialien und Schutzvorkehrungen gegen Hochspannung)

### Schritt-für-Schritt-Anleitung

1. **Flyback-Treiber anschließen**:
   - Verbinde den Eingang des Flyback-Moduls mit einer 12V bis 24V DC-Stromquelle.
   - Verbinde das Audioeingangssignal (z. B. über einen 3,5mm Klinkenstecker) mit der Audioquelle (Smartphone, Laptop, etc.).

2. **Zeilentrafo anschließen**:
   - Der Ausgang des Flyback-Transformators wird an die Eingänge des Zeilentrafos angeschlossen.

3. **Testen**:
   - Spiele Musik von deiner Audioquelle ab und höre, wie das Signal über den Zeilentrafo ausgegeben wird.

## Sicherheitshinweise

- **Hochspannung**: Der Flyback-Treiber erzeugt Hochspannungen. Arbeite daher sehr vorsichtig und befolge alle Sicherheitsvorkehrungen, um Verletzungen durch Stromschläge zu vermeiden.
- **Isolierung**: Stelle sicher, dass alle Hochspannungsleitungen gut isoliert sind und keine Kurzschlüsse entstehen.
- **Schutzbrille und Handschuhe**: Trage immer Schutzbrille und isolierende Handschuhe, wenn du mit Hochspannung arbeitest.

## Anwendungen

- **Experimentelle Musikprojekte**: Nutze den Flyback-Treiber zur Erzeugung einzigartiger Klänge in einer Musikinstallation.
- **Kunstinstallationen**: Setze die Technologie in interaktive oder künstlerische Audioprojekte ein.
- **Prototyping**: Nutze das Setup als Grundlage für eigene Experimente im Bereich Audio- und Elektrotechnik.

## Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Siehe [LICENSE](LICENSE) für weitere Details.

## Kontakt

- **E-Mail:** thomas.gruber@htlstp.at
- **GitHub:** github.com/codi668
