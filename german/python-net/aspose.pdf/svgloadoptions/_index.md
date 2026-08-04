---
title: "SvgLoadOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt Optionen zum Laden/Importieren von SVG-Dateien in ein PDF-Dokument dar."
type: docs
weight: 1450
url: /de/python-net/aspose.pdf/svgloadoptions/
---

## SvgLoadOptions class

Stellt Optionen zum Laden/Importieren von SVG-Dateien in ein PDF-Dokument dar.

Der Typ SvgLoadOptions stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| SvgLoadOptions() | Initialisiert eine neue Instanz der Klasse SvgLoadOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| warning_handler | Rückruf, um alle erzeugten Warnungen zu behandeln. <br/>            Der WarningHandler gibt ein ReturnAction-Enum-Element zurück, das entweder Continue oder Abort angibt. <br/>            Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, jedoch kann der Benutzer auch Abort zurückgeben, in welchem Fall der Ladevorgang beendet werden sollte. |
| load_format | Stellt das Dateiformat dar, das von [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) beschrieben wird. |
| page_info | Liest oder setzt Seiteninformationen, die beim Laden des Dokuments angewendet werden sollen.<br/>            HINWEIS: Dieser Parameter funktioniert nur, wenn ConversionEngine == ConversionEngines.NewEngine |
| adjust_page_size | Passt die PDF-Seitengröße an die SVG-Größe an |
| conversion_engine | Ermöglicht die Auswahl der Konvertierungs-Engine, die während der Konvertierung verwendet wird.<br/>            Derzeit befindet sich die neue Engine in der B-Testphase, sodass dieser Wert standardmäßig auf <br/>            ConversionEngines.LegacyEngine gesetzt wird. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

