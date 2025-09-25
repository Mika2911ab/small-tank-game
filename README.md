# Tiny Tanks — PyQt5 Game

Ein kleines 2D-Tankspiel in **Python/PyQt5**: Spiele **PvE** gegen eine einfache KI oder **PvP** gegen einen zweiten Spieler am selben Rechner.  
Fahre über zufällig generierte Maps, passe den Winkel und die Schussstärke an, berücksichtige **Wind**, und zerlege die Landschaft mit **destruierbaren Kratern**.

## 🎮 Features
- **Spielmodi:** PvE (gegen KI) und PvP (lokal, 2 Spieler)
- **Physik & Wind:** Projektilflug mit Schwerkraft und dynamischem Wind
- **Destruierbare Umgebung:** Einschläge erzeugen Krater, Terrain beeinflusst Bewegung & Treffer
- **Random Maps:** Gelände wird pro Start neu generiert (`standardMap.py`)
- **HUD:** Health-, Fuel- und Power-Anzeigen für beide Tanks
- **Partikel-Effekte:** Explosionen mit Funken/Trümmern

## 🕹️ Steuerung
- **Links/Rechts:** Panzer bewegen (Fuel wird verbraucht, Kollisionen/Steigungen werden geprüft)
- **Pfeil hoch/runter:** Kanonenwinkel anpassen
- **Leertaste (halten & loslassen):** Schussstärke aufladen & feuern
- **Rundenbasiert:** Grün beginnt; nach jedem Schuss ist der andere dran

## 🧠 KI (kurz)
- Positioniert sich grob gegenüber dem Spieler
- Passt Winkel/Power basierend auf dem letzten Einschlag an
- Nutzt denselben Physik/Wind-Stack wie der Spieler

## Contributors
- [Mikael Alves Brito](https://github.com/Mika2911ab)
- [Viktor Lehnhausen](https://github.com/vlehnhau)