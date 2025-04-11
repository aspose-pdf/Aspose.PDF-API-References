---
title: Class StartEndPageEventArgs
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.Printing.StartEndPageEventArgs. Fournit des données pour les événements StartPage et EndPage de la classe PdfViewer
type: docs
weight: 9710
url: /fr/net/aspose.pdf.printing/startendpageeventargs/
---
## Classe StartEndPageEventArgs

Fournit des données pour les événements [`StartPage`](../../aspose.pdf.facades/pdfviewer/startpage/) et [`EndPage`](../../aspose.pdf.facades/pdfviewer/endpage/) de la classe [`PdfViewer`](../../aspose.pdf.facades/pdfviewer/).

```csharp
public sealed class StartEndPageEventArgs : EventArgs
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [StartEndPageEventArgs](startendpageeventargs/)(int, int, int, int) | Initialise une nouvelle instance de la classe `StartEndPageEventArgs`. |

## Champs

| Nom | Description |
| --- | --- |
| readonly [CurrentCopy](../../aspose.pdf.printing/startendpageeventargs/currentcopy/) | Obtient le numéro de la copie actuellement en cours d'impression. |
| readonly [CurrentPage](../../aspose.pdf.printing/startendpageeventargs/currentpage/) | Obtient le numéro de la page actuellement en cours d'impression. |
| readonly [TotalCopies](../../aspose.pdf.printing/startendpageeventargs/totalcopies/) | Obtient le nombre total de copies à imprimer. |
| readonly [TotalPages](../../aspose.pdf.printing/startendpageeventargs/totalpages/) | Obtient le nombre total de pages à imprimer. |

### Voir aussi

* namespace [Aspose.Pdf.Printing](../../aspose.pdf.printing/)
* assembly [Aspose.PDF](../../)