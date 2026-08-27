---
title: "GraphicalPdfComparer.ComparePagesToPdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "GraphicalPdfComparer‑metod. Jämför sidor grafiskt. Jämförelsens resultat placeras i ett PDF‑dokument."
type: docs
weight: 80
url: /sv/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Jämför sidor grafiskt. Jämförelsresultatet placeras i ett PDF-dokument.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page1 | Page | Den första sidan. |
| page2 | Page | Den andra sidan. |
| resultPdfPath | String | Sökvägen till mål‑pdf‑filen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Om de jämförda sidorna har olika storlekar. Om resultPdfPath är null eller en tom sträng. |

### Se även

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Jämför sidor grafiskt. Jämförelsresultatet placeras i ett PDF-dokument.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page1 | Page | Den första sidan. |
| page2 | Page | Den andra sidan. |
| pdfDocument | Dokument | pdf-dokumentinstansen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Om de jämförda sidorna har olika storlekar. |

### Se även

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


