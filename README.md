# FloraOOEiNat
Anzeige aller Pflanzenfunde von iNaturalist für Oberösterreich

# iNaturalist Viewer für Oberösterreich

Dieses Projekt zeigt Beobachtungen von **Gefäßpflanzen** (Tracheophyta) aus Oberösterreich (place_id 10466) mithilfe der öffentlichen iNaturalist API. Es ist als kleine Webanwendung gebaut und kann über GitHub Pages betrieben werden.

## Funktionen

- Auswahl eines Datumsbereichs (standardmäßig aktuelle Woche)
- Filter für **verifizierte Beobachtungen** (research grade)
- Blättern durch Seiten (`per_page = 20`)
- Anzeige von:
  - wissenschaftlichem Namen
  - Beobachter
  - Datum
  - Fundort
  - Koordinaten (sofern vorhanden)
  - Bild (sofern vorhanden)
- **Export als CSV** (zwei Formate):
  - Normales CSV (`inat_ooe_beobachtungen.csv`)
  - ZOBODAT-kompatibles CSV (`inat_ooe_zobodat.csv`)

## Nutzung

1. Öffne die Seite im Browser (z. B. via GitHub Pages).
2. Wähle einen Datumsbereich.
3. Klicke auf „Daten laden“.
4. Optional: Filtere auf „Nur verifizierte Beobachtungen“.
5. Blättere mit „Zurück“ und „Weiter“.
6. Lade Daten als CSV oder ZOBODAT-Datei herunter.

## Technologie

- HTML & Vanilla JavaScript
- [iNaturalist API v1](https://api.inaturalist.org/v1/docs/)
- Datenquelle: öffentlich zugängliche iNaturalist-Beobachtungen

## Lizenz

MIT-Lizenz – frei verwendbar unter Nennung der Quelle.

## Hinweis

Dieses Tool dient zur Erleichterung der Datenrecherche und zum Export für persönliche oder wissenschaftliche Zwecke. Die Daten stammen direkt von iNaturalist und können dort laufend aktualisiert werden.
