---
title: "PclLoadOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt Optionen zum Laden (Import) einer PCL‑Datei in ein PDF‑Dokument dar."
type: docs
weight: 1170
url: /de/python-net/aspose.pdf/pclloadoptions/
---

## PclLoadOptions class

Stellt Optionen zum Laden (Import) einer PCL‑Datei in ein PDF‑Dokument dar.

Der Typ PclLoadOptions stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PclLoadOptions() | Initialisiert eine neue Instanz der Klasse PclLoadOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| warning_handler | Rückruf, um alle erzeugten Warnungen zu behandeln. <br/>            Der WarningHandler gibt ein ReturnAction-Enum-Element zurück, das entweder Continue oder Abort angibt. <br/>            Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, jedoch kann der Benutzer auch Abort zurückgeben, in welchem Fall der Ladevorgang beendet werden sollte. |
| load_format | Stellt das Dateiformat dar, das von [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) beschrieben wird. |
| batch_size | Definiert die Batch‑Größe, wenn das Attribut 'SplitOnPages=false' ist, wird das gesamte HTML, das alle Eingabe‑PDF‑Seiten darstellt, nicht<br/>            in verschiedene HTML‑Seiten aufgeteilt, sondern in einer großen Ergebnis‑HTML‑Datei zusammengefasst.<br/>            Jede Quell‑PDF‑Seite wird jedoch mit ihrem eigenen <br/>            rechteckigen Bereich in HTML dargestellt (falls nötig können diese Bereiche mit dem speziellen Attribut 'PageBorderIfAny' begrenzt werden, um die Kanten des Papierblatts zu zeigen).<br/>            Dieser Parameter definiert die Breite des Randes, der zwingend um die Ausgab‑HTML‑Bereiche, die die Seiten des Quell‑PDF‑Dokuments repräsentieren, gelassen wird.<br/>            Im Wesentlichen definiert er das garantierte Intervall zwischen den HTML‑Darstellungen der PDF‑„Papier“‑Seiten bei dieser Konvertierungsart. |
| conversion_engine | Definiert die Konvertierungs-Engine, die für die Umwandlung verwendet wird |
| supress_errors | Liest oder setzt den booleschen Wert, der angibt, ob PCL-Konvertierungsfehler unterdrückt werden sollen. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

