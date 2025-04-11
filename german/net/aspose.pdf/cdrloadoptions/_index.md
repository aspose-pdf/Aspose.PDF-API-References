---
title: Class CdrLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CdrLoadOptions-Klasse. Klasse beschreibt CDR-Ladeoptionen
type: docs
weight: 2960
url: /de/net/aspose.pdf/cdrloadoptions/
---
## CdrLoadOptions-Klasse

Klasse beschreibt CDR-Ladeoptionen.

```csharp
public class CdrLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CdrLoadOptions](cdrloadoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft ein Flag ab oder legt es fest, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel erlaubt es, eine Schriftart in ein PDF-Dokument einzubetten, selbst wenn die Lizenzregeln das Einbetten dieser Schriftart deaktivieren. Standardmäßig `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Ladevorgang eingestellt werden. |

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)