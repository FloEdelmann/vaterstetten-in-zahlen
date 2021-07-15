# ArcGIS-API des Landratsamtes Ebersberg

Das [Covid-19 Dashboard Ebersberg](https://experience.arcgis.com/experience/dc7f97a7874b47aebf1a75e74749c047) des Landkreises Ebersberg benutzt als Backend eine ArcGIS REST API: https://services-eu1.arcgis.com/CZ1GXX3MIjSRSHoC/ArcGIS/rest/services

Diese API beinhaltet folgende Tabellen (sog. *FeatureServer*):

- CoronaIndexListe_21_04_2021_Gemeinde_GebJahr
- CoronaIndexListe_Gemeinde (einzelne Fälle nach Meldedatum, Geburtsjahr und Ort, zwischen 2021-01-02 und 2021-04-21)
- EBE_Gemeindegrenzen_2018_mit_Einwohnerzahl
- EBE_Gemeinden_Inzidenztabelle
- EBE_Landkreis_Inzidenztabelle
- Ebersberg_Gemeindegrenzen
- Sicht___EBE_Gemeinden_mit_Inzidenzen_aktuell

Dokumentation zur Benutzung von ArcGIS REST API Feature Services: https://developers.arcgis.com/rest/services-reference/enterprise/query-feature-service-.htm

Und Benutzung in Python: https://developers.arcgis.com/python/guide/working-with-feature-layers-and-features/