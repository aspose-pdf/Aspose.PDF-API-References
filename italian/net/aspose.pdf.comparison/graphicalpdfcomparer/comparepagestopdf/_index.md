---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: Metodo GraphicalPdfComparer. Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF
type: docs
weight: 80
url: /it/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | La prima pagina. |
| page2 | Page | La seconda pagina. |
| resultPdfPath | String | Il percorso del file pdf di destinazione. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Se le pagine confrontate sono di dimensioni diverse. Se resultPdfPath è nullo o una stringa vuota. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | La prima pagina. |
| page2 | Page | La seconda pagina. |
| pdfDocument | Document | L'istanza del documento pdf. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Se le pagine confrontate sono di dimensioni diverse. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)