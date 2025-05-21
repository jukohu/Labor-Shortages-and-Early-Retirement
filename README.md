# Fachkräftemangel & Frühverrentung – Datenbeschaffung,-konsolidierung und -analyse

## Projektbeschreibung
Dieses Projekt fokussiert sich auf die Erhebung von Daten, die relevant sein können, um den Zusammenhang zwischen Fachkräftemangel und Frühverrentung in Deutschland zu analysieren. Ziel war es, geeignete Datenquellen zu finden, zusammenzuführen und eine Datenbasis für weitere ökonometrische Auswertungen zu schaffen. Dieser Prozess erforderte die Erarbeitung einer Webscrapingstrategie, da die benötigten Arbeitsmarktdaten zwar öffentlich zugänglich auf der Webseite der Bundesagentur für Arbeit erhältlich sind, aber nicht in einer csv oder xlxs Datei zusammengefügt sondern in unterschiedlichen Dateien und teilweise im PDF-Format.

## Datenquellen
- [1.	Gemeldete Arbeitsstellen nach Berufen (Engpassanalysen) – Länder (Monatszahlen)](https://statistik.arbeitsagentur.de/SiteGlobals/Forms/Suche/Einzelheftsuche_Formular.html?topic_f=analyse-gemeldete-arbeitsstellen-kldb2010 )
- [2.	Bewerber und Berufsausbildungsstellen – Deutschland, West/Ost, Länder, Kreise, Regionaldirektionen und Agenturen mit Geschäftsstellen (Monatszahlen)]([https://www-genesis.destatis.de/](https://statistik.arbeitsagentur.de/SiteGlobals/Forms/Suche/Einzelheftsuche_Formular.html?nn=1459818&topic_f=ausb-ausbildungsstellenmarkt-mit-zkt))
- [3.	Arbeitsmarkt nach Berufen (KldB 2010) – Deutschland, West/Ost und Länder (Monatszahlen)](https://statistik.arbeitsagentur.de/SiteGlobals/Forms/Suche/Einzelheftsuche_Formular.html?r_f=bl_Baden-Wuerttemberg&topic_f=berufe-heft-kldb2010)

Die Daten wurden mit Python automatisiert verarbeitet.

## Verwendeter Code

