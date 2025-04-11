---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SaveOptions-Klasse. Der Typ SaveOptions hält das Abstraktionsniveau für einzelne Speicheroptionen
type: docs
weight: 9870
url: /de/net/aspose.pdf/saveoptions/
---
## Klasse SaveOptions

Der Typ SaveOptions hält das Abstraktionsniveau für einzelne Speicheroptionen

```csharp
public abstract class SaveOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob Schriftart-Glyphen während der Vorbereitung von APS-Seiten zwischengespeichert werden. Verbessert die Leistung der Konvertierung von PDF in andere Formate, erhöht jedoch den Speicherverbrauch. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob das Response-Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format der gespeicherten Daten. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speicherprozess wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Speicherprozess eingestellt werden. |

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)