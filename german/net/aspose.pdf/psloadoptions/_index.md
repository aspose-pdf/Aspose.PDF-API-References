---
title: Class PsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PsLoadOptions-Klasse. Stellt Optionen zum Laden/Importieren von .mht-Dateien in ein PDF-Dokument dar
type: docs
weight: 9730
url: /de/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions-Klasse

Stellt Optionen zum Laden/Importieren von .mht-Dateien in ein PDF-Dokument dar.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft ein Flag ab oder legt es fest, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF-Dokument, selbst wenn die Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Standardmäßig `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Ruft die Pfade der Schriftartenordner ab oder legt sie fest. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Ladevorgang eingestellt werden. |

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)