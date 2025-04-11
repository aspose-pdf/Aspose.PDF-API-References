---
title: Class SaveableFacade
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.SaveableFacade-Klasse. Basisklasse für alle speicherbaren Fassaden
type: docs
weight: 4700
url: /de/net/aspose.pdf.facades/saveablefacade/
---
## Klasse SaveableFacade

Basisklasse für alle speicherbaren Fassaden.

```csharp
public abstract class SaveableFacade : Facade, ISaveableFacade
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gibt die Dokumentenfassade zurück, an der gearbeitet wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialisiert die Fassade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialisiert die Fassade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Gibt das mit einer Fassade verbundene Aspose.Pdf.Document frei. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Gibt die Fassade frei. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save)(Stream) | Speichert das PDF-Dokument im angegebenen Stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save_1)(string) | Speichert das PDF-Dokument in der angegebenen Datei. |

### Siehe auch

* Klasse [Facade](../facade/)
* Schnittstelle [ISaveableFacade](../isaveablefacade/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)