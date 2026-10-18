# Bitfocus-Companion-Modul: Allen & Heath Avantis Assign

[English](README.md) · **Deutsch**

Ein Modul für [Bitfocus Companion](https://bitfocus.io/companion), das kann, was das offizielle Avantis-Modul nicht kann: **das Assign eines Eingangs auf Aux-Mixe schalten**, mit Live-Rückmeldung vom Pult. Ideal für Talkback auf einem Stream Deck.

> [!NOTE]
> **In Entwicklung.** Noch nichts zu installieren. Beobachte das Repo oder gib einen Stern, dann bekommst du Bescheid. Baut auf der Protokoll-Arbeit aus **[allenheath-talkback](https://github.com/Floslis/allenheath-talkback)** auf, dokumentiert in **[avantis-protocol](https://github.com/Floslis/avantis-protocol)**.

[![Unterstütze mich auf Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/floslist)

## Warum

Das offizielle [Avantis-Modul](https://github.com/bitfocus/companion-module-allenheath-avantis) spricht MIDI über TCP. Damit gehen Fader, Mutes und Szenen, aber per MIDI lässt sich kein Eingang auf einen Mix zuweisen. Dieses Modul nutzt dafür das native Protokoll des Pults (das von Director und Mixing Station) und läuft neben dem offiziellen Modul.

## Geplant

**Aktionen**
- [ ] Assign Eingang → Aux / Stereo-Aux: an, aus, umschalten
- [ ] Gruppen von Mixen mit einem Druck (z. B. „Band“, „MD“), wie in allenheath-talkback
- [ ] Send-Pegel Eingang → Aux

**Rückmeldungen**
- [ ] Taste leuchtet, wenn ein Assign an ist, live vom Pult, auch wenn am Pult geändert
- [ ] Mix-Namen vom Pult als Tastentext

**Außerdem**
- [ ] Pult im Netz automatisch finden
- [ ] Vorlagen für eine Talkback-Seite
- [ ] Veröffentlichung im Companion-Modul-Store

## Stand

| | |
|---|---|
| Protokoll (verbinden, Lebenszeichen, Assign, Live-Zustand) | ✅ läuft in [allenheath-talkback](https://github.com/Floslis/allenheath-talkback) |
| Companion-Modul | 🚧 noch nicht begonnen |
| Getestet | Avantis Firmware V2.01 Rev. 97241 |

Lust zu helfen oder zu testen? Mach ein Issue auf.

## Lizenz

[MIT](LICENSE), weil Bitfocus für Module in Companion MIT verlangt. Das Talkback-Tool und die Treiber dahinter stehen unter AGPL-3.0 · Nicht mit Allen & Heath oder Bitfocus verbunden · Ein Projekt von **[FLOTECH](https://flotech.dev)**
