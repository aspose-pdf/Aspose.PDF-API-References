---
title: Class StartEndPageEventArgs
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.Printing.StartEndPageEventArgs. Fornisce dati per gli eventi StartPage e EndPage della classe PdfViewer
type: docs
weight: 9710
url: /it/net/aspose.pdf.printing/startendpageeventargs/
---
## Classe StartEndPageEventArgs

Fornisce dati per gli eventi [`StartPage`](../../aspose.pdf.facades/pdfviewer/startpage/) e [`EndPage`](../../aspose.pdf.facades/pdfviewer/endpage/) della classe [`PdfViewer`](../../aspose.pdf.facades/pdfviewer/).

```csharp
public sealed class StartEndPageEventArgs : EventArgs
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [StartEndPageEventArgs](startendpageeventargs/)(int, int, int, int) | Inizializza una nuova istanza della classe `StartEndPageEventArgs`. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [CurrentCopy](../../aspose.pdf.printing/startendpageeventargs/currentcopy/) | Ottiene il numero della copia attualmente in fase di stampa. |
| readonly [CurrentPage](../../aspose.pdf.printing/startendpageeventargs/currentpage/) | Ottiene il numero della pagina attualmente in fase di stampa. |
| readonly [TotalCopies](../../aspose.pdf.printing/startendpageeventargs/totalcopies/) | Ottiene il numero totale di copie da stampare. |
| readonly [TotalPages](../../aspose.pdf.printing/startendpageeventargs/totalpages/) | Ottiene il numero totale di pagine da stampare. |

### Vedi Anche

* namespace [Aspose.Pdf.Printing](../../aspose.pdf.printing/)
* assembly [Aspose.PDF](../../)