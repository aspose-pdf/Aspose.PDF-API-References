---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgLoadOptions-Klasse. Stellt Optionen zum Laden/Importieren von SVG-Dateien in ein PDF-Dokument dar
type: docs
weight: 10210
url: /de/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions-Klasse

Stellt Optionen zum Laden/Importieren von SVG-Dateien in ein PDF-Dokument dar.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Passt die PDF-Seitengröße an die SVG-Größe an |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft ein Flag ab oder legt es fest, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel erlaubt es, eine Schriftart in ein PDF-Dokument einzubetten, auch wenn die Lizenzregeln das Einbetten dieser Schriftart deaktivieren. Standardmäßig `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Ruft die Seiteninformationen ab oder legt sie fest, die beim Laden des Dokuments angewendet werden sollen. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein ReturnAction-Enum-Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Ladevorgang eingestellt werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Ermöglicht die Auswahl des Konvertierungs-Engines, das während der Konvertierung verwendet wird. Derzeit befindet sich der neue Engine in der B-Testphase, daher ist dieser Wert standardmäßig auf ConversionEngines.LegacyEngine gesetzt. |

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)