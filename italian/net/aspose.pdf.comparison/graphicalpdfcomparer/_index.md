---
title: Class GraphicalPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.GraphicalPdfComparer. Rappresenta una classe per confrontare graficamente documenti PDF. Dovrebbe essere utilizzata per cercare piccole modifiche principalmente di natura grafica. Per confrontare le modifiche nel contenuto testuale, utilizzare altre classi di confronto PDF.
type: docs
weight: 3190
url: /it/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## Classe GraphicalPdfComparer

Rappresenta una classe per confrontare graficamente documenti PDF. Dovrebbe essere utilizzata per cercare piccole modifiche, principalmente di natura grafica. Per confrontare le modifiche nel contenuto testuale, utilizzare altre classi di confronto PDF.

```csharp
public class GraphicalPdfComparer
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Ottiene e imposta il colore del flag di cambiamento. Il colore predefinito è rosso. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Ottiene e imposta la risoluzione delle immagini risultanti. Il valore predefinito è 150dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Ottiene e imposta il valore della soglia in percentuale. Questo valore consente di ignorare piccole modifiche se non sono significative per te. Il valore predefinito è 0%. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Confronta documenti graficamente. Il risultato del confronto è posizionato in immagini. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Confronta documenti graficamente. Il risultato del confronto è posizionato in un documento PDF. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Confronta pagine graficamente. Il risultato del confronto è posizionato in un'immagine. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Confronta pagine graficamente. Il risultato del confronto è posizionato in un documento PDF. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Confronta pagine graficamente. Il risultato del confronto è posizionato in un documento PDF. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Ottiene le differenze tra le immagini delle pagine. Il risultato contiene un'immagine della prima pagina confrontata e un array di differenze. |

### Vedi Anche

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)