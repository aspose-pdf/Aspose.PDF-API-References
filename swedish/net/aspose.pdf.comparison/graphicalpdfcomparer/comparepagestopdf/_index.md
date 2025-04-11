---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer-metod. Jämför sidor grafiskt. Jämförelseresultatet placeras i ett PDF-dokument
type: docs
weight: 80
url: /sv/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Jämför sidor grafiskt. Jämförelseresultatet placeras i ett PDF-dokument.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page1 | Page | Den första sidan. |
| page2 | Page | Den andra sidan. |
| resultPdfPath | String | Sökvägen till målpdf-filen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Om de sidor som jämförs har olika storlekar. Om resultPdfPath är null eller en tom sträng. |

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* klass [GraphicalPdfComparer](../)
* namnrymd [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Jämför sidor grafiskt. Jämförelseresultatet placeras i ett PDF-dokument.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page1 | Page | Den första sidan. |
| page2 | Page | Den andra sidan. |
| pdfDocument | Document | PDF-dokumentinstansen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Om de sidor som jämförs har olika storlekar. |

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* klass [Document](../../../aspose.pdf/document/)
* klass [GraphicalPdfComparer](../)
* namnrymd [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)