# GIS-MCDA-Framework zur Standortanalyse von Batteriespeichersystemen 

Dieses Repository enthält die im Rahmen meiner Masterarbeit verwendeten Geodaten, QGIS-Projektdateien, Python-Skripte sowie zentrale Analyse- und Ergebnisdateien. 

Die Untersuchung umfasst ein Macro-Screening für Brandenburg und eine GIS-MCDA-Detailanalyse für den Landkreis Teltow-Fläming. 

## Ordnerstruktur
- daten/
    - 01_ausgangsdaten/
    - 02_macro_screening/
    - 03_detailanalyse_teltow_flaeming/
    - 04_mcda_sensitivitaet/

- qgis_projekt/
    - BESS_GIS_MCDA_Masterarbeit_Kalkan_Nisa.qgz
    - QGIS-Projekt mit relativen Datenpfaden zur bereitgestellten Ordnerstruktur 

- scripts/
    - mcda_szenario_berechnung.py 
    - mcda_sensitivitaet_batch.py

- ergebnisse/
     - Karten, Abbildungen und Ergebnistabellen 

## Software 
Die Analyse wurde mit QGIS 3.34.12 ,,Prizren" durchgeführt. 

Koordinatenreferenzsystem: 
`ETRS89/UTM Zone 33N (EPSG:25833)`

## Reproduzierbarkeit
Das Repository enthält die zentralen Eingangsdaten, Analyse- und Ergebnislayer sowie die verwendeten Skripte. 

Nicht alle während der Bearbeitung entstandenen technischen Zwischenlayer sind Bestandteil des Repositories. Die relevanten Verarbeitungsschritte und Parameter sind in der Masterarbeit dokumentiert. 


## Vollständige Projektdateien 
Aufgrund der Größe einzelner Geodateien werden die vollständigen Projektdateien zusätzlich über einen Cloud-Speicher bereitgestellt. 


**Cloud-Link:**
[vollständige Proejktdtaeien in der Cloud](https://cloud.bht-berlin.de/index.php/s/6tcZKrB8wSydsND)

## Masterarbeit 
Die vollständige Beschreibung der Methodik, Datenaufbereitung, MCDA, Sensitivitätsanalyse und internen Validierung befindet sich in der zugehörigen Masterarbeit: 
**,,Entwicklung und Validierung eines multikriteriellen Entscheidungsmodells für die automatisierte Standortanalyse von Batteriespeichern (BESS)."**




