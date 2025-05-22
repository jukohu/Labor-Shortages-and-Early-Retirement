# Fachkräftemangel & Frühverrentung – Datenbeschaffung,-konsolidierung und -analyse

## Projektbeschreibung
Dieses Projekt fokussiert sich auf die Erhebung von Daten, die relevant sein können, um den Zusammenhang zwischen Fachkräftemangel und Frühverrentung in Deutschland zu analysieren. Ziel war es, geeignete Datenquellen zu finden, zusammenzuführen und eine Datenbasis für weitere ökonometrische Auswertungen zu schaffen. Dieser Prozess erforderte die Erarbeitung einer Webscrapingstrategie, da die benötigten Arbeitsmarktdaten zwar öffentlich zugänglich auf der Webseite der Bundesagentur für Arbeit erhältlich sind, aber nicht in einer csv oder xlxs Datei zusammengefügt sondern in unterschiedlichen Dateien und teilweise im PDF-Format.

## Datenquellen
- [1.	Gemeldete Arbeitsstellen nach Berufen (Engpassanalysen) – Länder (Monatszahlen)](https://statistik.arbeitsagentur.de/SiteGlobals/Forms/Suche/Einzelheftsuche_Formular.html?topic_f=analyse-gemeldete-arbeitsstellen-kldb2010 )
- [2.	Bewerber und Berufsausbildungsstellen – Deutschland, West/Ost, Länder, Kreise, Regionaldirektionen und Agenturen mit Geschäftsstellen (Monatszahlen)](https://statistik.arbeitsagentur.de/SiteGlobals/Forms/Suche/Einzelheftsuche_Formular.html?nn=1459818&topic_f=ausb-ausbildungsstellenmarkt-mit-zkt)
- [3.	Arbeitsmarkt nach Berufen (KldB 2010) – Deutschland, West/Ost und Länder (Monatszahlen)](https://statistik.arbeitsagentur.de/SiteGlobals/Forms/Suche/Einzelheftsuche_Formular.html?r_f=bl_Baden-Wuerttemberg&topic_f=berufe-heft-kldb2010)

Die Daten wurden mit Python automatisiert verarbeitet.

## Notebooks im Überblick


| [A WebscrapingGemeldete Arbeitsstellen nach Berufen](Jupyter_Notebooks/A_Webscraping_Gemeldete%20Arbeitsstellen%20nach%20Berufen.ipynb) | Extrahiert gemeldete Arbeitsstellen nach Berufen aus BA Dateien. |
| [B Webscraping Bewerber und Berufsausbildungsstellen](Jupyter_Notebooks/B_Webscraping_Bewerber%20und%20Berufsausbildungsstellen.ipynb) | Extrahiert Bewerberzahlen und Ausbildungsstellen. |
| [C Webscraping Labor Market Tightness](Jupyter_Notebooks/C_Webscraping_Labor_Market_Tightness.ipynb) | Berechnung des `V/S`-Verhältnisses. |
| [C2_Rentendaten](Jupyter_Notebooks/C2_Rentendaten.ipynb) | Bereinigt Rentenzugangsdaten. |
| [D Merging and Consolidating Data](Jupyter_Notebooks/D_Merging%20and%20Consolidating%20Data%20into%20one%20Data%20Frame%20%28%2B%20standardizing%20it%20by%20indexing%29.ipynb) | Datenzusammenführung und Standardisierung. |
| [E_Analysis of Merged Data](Jupyter_Notebooks/E_Analysis%20of%20Merged%20Data.ipynb) | Explorative Analyse und Visualisierung. |

## Datenzugang

[Klicke hier um auf Alle Daten zu zugreifen](https://1drv.ms/u/s!Aexample123?e=abcDEF](https://diwberlinev-my.sharepoint.com/:f:/g/personal/agehlen_diw_de/EjiY0sbxQNpHvfjI1RQsI2MBAhb35hG97wpXhIdKL4bIkg?e=MwHQ9y)


