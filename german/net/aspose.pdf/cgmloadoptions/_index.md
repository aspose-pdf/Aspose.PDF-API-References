---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CgmLoadOptions class. Contains options for loading/importing CGM file into pdf document
type: docs
weight: 3010
url: /de/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions-Klasse

Enthält Optionen zum Laden/Importieren von CGM-Dateien in ein PDF-Dokument.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Erstellt Standardladeoptionen zum Konvertieren von CGM-Dateien in ein PDF-Dokument. Standard-PDF-Seitengröße - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Erstellt Ladeoptionen mit definierter !:pageSize. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft ein Flag ab oder legt es fest, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel erlaubt es, eine Schriftart in ein PDF-Dokument einzubetten, auch wenn die Lizenzregeln das Einbetten dieser Schriftart deaktivieren. Standardmäßig `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Ruft die Ausgabeseitengröße für den Import ab oder legt sie fest. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Ladevorgang eingestellt werden. |

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)