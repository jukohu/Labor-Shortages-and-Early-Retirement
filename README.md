# Fachkräftemangel & Frühverrentung – Datenbeschaffung,-konsolidierung und -analyse

## Projektbeschreibung
Dieses Projekt fokussiert sich auf die Erhebung von Daten, die relevant sein können, um den Zusammenhang zwischen Fachkräftemangel und Frühverrentung in Deutschland zu analysieren. Ziel war es, geeignete Datenquellen zu finden, zusammenzuführen und eine Datenbasis für weitere ökonometrische Auswertungen zu schaffen. Dieser Prozess erforderte die Erarbeitung einer Webscrapingstrategie, da die benötigten Arbeitsmarktdaten zwar öffentlich zugänglich auf der Webseite der Bundesagentur für Arbeit erhältlich sind, aber nicht in einer csv oder xlxs Datei zusammengefügt sondern in unterschiedlichen Dateien und teilweise im PDF-Format.

## 📁 Struktur des Reposatory's


## 🔗 Datenquellen
- [Bundesagentur für Arbeit – Engpassanalyse](https://statistik.arbeitsagentur.de/)
- [Destatis – Rentenzugang nach Altersgruppen](https://www-genesis.destatis.de/)
- [OECD – Erwerbsquoten nach Alter](https://data.oecd.org/)

Die meisten Daten wurden manuell heruntergeladen. Einige wurden mit Python automatisiert verarbeitet.

## 🐍 Verwendeter Code
- `scripts/combine_vacancy_data.py`: Kombiniert PDF-Tabellen der Engpassanalyse
- `scripts/clean_rentendaten.py`: Bereinigt Rentenzugänge nach Bundesland und Altersgruppe
- `scripts/merge_all.py`: Führt alles in eine Master-Datei zusammen

## 📈 Nächste Schritte
- Zeitreihenanalyse auf regionaler Ebene
- Ökonometrisches Modell (z.B. Paneldatenregression)
- Visualisierung mit Plotly / Seaborn

## 📄 Lizenz
Dieses Projekt dient nur Forschungszwecken. Die verwendeten Daten unterliegen den Lizenzbedingungen der jeweiligen Anbieter.
