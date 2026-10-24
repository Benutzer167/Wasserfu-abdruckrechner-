# 💧 Wasserfußabdruck-Rechner

**Ein interaktiver Rechner zur Schätzung des persönlichen Wasserfußabdrucks.**

Wie viel Wasser verbrauchen wir wirklich? Nicht nur beim Duschen oder Wäschewaschen, sondern auch indirekt durch Lebensmittel, Kleidung und Energie?

Der Wasserfußabdruck-Rechner macht diesen oft unsichtbaren Wasserverbrauch greifbar. Anhand von 11 Fragen zum persönlichen Lebensstil wird der geschätzte tägliche Wasserverbrauch berechnet, visualisiert und mit dem deutschen Durchschnitt verglichen.

## Funktionen

- **Interaktiver Fragebogen:** 11 Fragen zu Haushalt, Ernährung, Kleidung und Energie.
- **Individuelle Berechnung:** Schätzung des täglichen Wasserfußabdrucks in Litern sowie des jährlichen Verbrauchs in Kubikmetern.
- **Vergleich mit Deutschland:** Grafischer Vergleich mit einem hinterlegten Referenzwert von 5.288 Litern pro Person und Tag.
- **Detaillierte Auswertung:** Aufschlüsselung des Wasserverbrauchs in fünf Kategorien.
- **Persönliche Empfehlungen:** Dynamisch generierte Tipps zur Reduzierung des Wasserverbrauchs.
- **Responsives Design:** Optimierte Darstellung auf Smartphones, Tablets und Desktopgeräten.
- **Keine Registrierung:** Direkte Nutzung ohne Benutzerkonto.

## Berücksichtigte Kategorien

| Kategorie | Berücksichtigte Faktoren |
|---|---|
| Haushalt | Haushaltsgröße, Duschverhalten, Wäschewaschen |
| Ernährung | Fleisch- und Fischkonsum, Milchprodukte, Kaffee und Tee, regionale Lebensmittel |
| Kleidung & Konsum | Neue Kleidungsstücke, Second-Hand-Kleidung |
| Energie | Stromversorgung, Heizungsart |
| Sonstiges | Pauschaler Grundwert für weitere Verbrauchsbereiche |

## Installation und Verwendung

Die Anwendung besteht aus einer einzigen HTML-Datei. Eine zusätzliche Installation, ein Framework oder ein Backend sind nicht erforderlich.

1. Repository herunterladen oder klonen.
2. Die HTML-Datei als `index.html` speichern.
3. `index.html` in einem modernen Webbrowser öffnen.
4. Den Fragebogen starten und die 11 Fragen beantworten.
5. Den persönlichen Wasserfußabdruck auswerten.

Die Anwendung kann alternativ über GitHub Pages veröffentlicht werden.

## Technologien

| Technologie | Verwendung |
|---|---|
| HTML5 | Struktur der Anwendung |
| CSS3 | Responsives Layout, Styling und Animationen |
| Vanilla JavaScript | Fragebogen, Berechnungslogik und Ergebnisdarstellung |
| Tabler Icons | Icons und visuelle Elemente |

Die Anwendung benötigt weder externe JavaScript-Frameworks noch einen Build-Prozess. Die Icons werden über ein CDN geladen.

## Berechnungsmethodik

Der Rechner verwendet ein vereinfachtes, regelbasiertes Schätzmodell.

Jede Antwort wird einem festgelegten Verbrauchswert beziehungsweise einem Gewichtungsfaktor zugeordnet. Daraus werden die einzelnen Verbrauchskategorien berechnet und anschließend addiert.

**Gesamter Wasserfußabdruck = Haushalt + Ernährung + Kleidung & Konsum + Energie + Sonstiges**

Der errechnete Tageswert wird zusätzlich auf ein Jahr hochgerechnet und mit einem hinterlegten deutschen Referenzwert verglichen.

### Wichtiger Hinweis

Die Ergebnisse stellen **modellbasierte Schätzungen und keine exakten Messwerte** dar. Die verwendeten Faktoren und Verbrauchswerte sind vereinfacht und können je nach Produkt, Herkunft, Produktionsbedingungen und persönlichem Lebensstil erheblich variieren.

Auch die Einordnung in Verbrauchsklassen dient lediglich der Orientierung.

Das Tool verfolgt einen edukativen Ansatz und soll insbesondere das Bewusstsein für den indirekten beziehungsweise virtuellen Wasserverbrauch stärken.

## Datenschutz

Der Fragebogen und die Berechnungen werden vollständig im Browser ausgeführt.

- Kein Benutzerkonto erforderlich
- Keine serverseitige Speicherung der Antworten
- Keine Übermittlung der Fragebogenantworten an ein Backend
- Keine eingebundenen Analyse- oder Trackingdienste im bereitgestellten Code

Für die Darstellung der Icons wird eine externe CSS-Ressource über jsDelivr geladen.

## Quellen und weiterführende Informationen

Die Anwendung nennt folgende Quellen als fachliche Orientierung:

- Umweltbundesamt (2021)
- WWF Deutschland
- Water Footprint Network (Hoekstra et al.)

Die konkreten Berechnungsfaktoren sind im JavaScript-Quellcode hinterlegt. Eine vollständige wissenschaftliche Validierung des Schätzmodells liegt nicht vor.

## Ziel des Projekts

Ziel ist es, komplexe Zusammenhänge zwischen alltäglichen Konsumentscheidungen und globalem Wasserverbrauch einfach, verständlich und interaktiv darzustellen.

Das Projekt verbindet Umweltbildung mit einer minimalistischen Benutzeroberfläche und soll zur Reflexion des eigenen Konsumverhaltens anregen.
