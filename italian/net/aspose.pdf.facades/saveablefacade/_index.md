---
title: Class SaveableFacade
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.SaveableFacade class. Base class for all saveable facades
type: docs
weight: 4700
url: /it/net/aspose.pdf.facades/saveablefacade/
---
## Classe SaveableFacade

Classe base per tutte le facciate salvabili.

```csharp
public abstract class SaveableFacade : Facade, ISaveableFacade
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene la facciata del documento su cui si sta lavorando. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inizializza la facciata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inizializza la facciata. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Rilascia Aspose.Pdf.Document associato a una facciata. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save)(Stream) | Salva il documento PDF nello stream specificato. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save_1)(string) | Salva il documento PDF nel file specificato. |

### Vedi Anche

* classe [Facade](../facade/)
* interfaccia [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)