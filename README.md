# berlin-bollards

In diesem Repository befinden sie die Daten und Konfigurationen, um mit QGIS alle Poller Berlins auf einer Karte darzustellen und Auswertungen vorzunehmen.

![Karte aller Poller](/export/karte-poller.png)

### Daten

Unter https://daten.berlin.de/datensaetze/straßenbefahrung-2014-poller-wfs-0 stellt das Land Berlin die Geodaten aller bei der Straßenbefahrung 2014 erfassten Poller zur Verfügung. Zusätzlich werden die [Ortsteile von Berlin](https://daten.berlin.de/datensaetze/ortsteile-von-berlin-wms) zur Analyse und für die verwendet

Die Daten für die Poller sind mit ogr2ogr ([GDAL](https://www.gdal.org/index.html)) am 16.04.2019 vom FIS-Broker heruntergeladen und konvertiert worden.

### Voraussetzungen:
* Unterstützung für [Git-LFS](https://git-lfs.github.com)
* [QGIS 3](https://www.qgis.org/en/site/) 