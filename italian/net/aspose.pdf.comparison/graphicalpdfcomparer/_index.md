---
title: "Classe GraphicalPdfComparer"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Comparison.GraphicalPdfComparer. Rappresenta una classe per confrontare graficamente i documenti PDF. Dovrebbe essere usata per cercare piccole modifiche principalmente di natura grafica. Per confrontare le modifiche al contenuto testuale utilizzare altre classi di confronto PDF."
type: docs
weight: 3300
url: /it/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class

Rappresenta una classe per confrontare graficamente i documenti PDF. Deve essere utilizzata per cercare piccole modifiche, principalmente di natura grafica. Per confrontare le modifiche al contenuto del testo, utilizzare altre classi di confronto PDF.

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
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | Ottiene e imposta il colore del flag di modifica. Il colore predefinito è rosso. |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | Ottiene e imposta la risoluzione delle immagini risultanti. Il valore predefinito è 150 dpi. |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | Ottiene e imposta il valore soglia in percentuale. Questo valore consente di ignorare piccole modifiche se non sono significative per te. Il valore predefinito è 0 %. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | Confronta i documenti graficamente. Il risultato del confronto è inserito nelle immagini. |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | Confronta i documenti graficamente. Il risultato del confronto è inserito in un documento PDF. |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | Confronta le pagine graficamente. Il risultato del confronto è inserito in un'immagine. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF. |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF. |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | Ottiene le differenze tra le immagini delle pagine. Il risultato contiene un'immagine della prima pagina confrontata e un array di differenze. |

### Vedi anche

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


