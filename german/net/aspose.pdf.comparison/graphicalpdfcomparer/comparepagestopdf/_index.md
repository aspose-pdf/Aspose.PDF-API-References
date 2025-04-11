---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer-Methode. Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument platziert
type: docs
weight: 80
url: /de/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument platziert.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page1 | Page | Die erste Seite. |
| page2 | Page | Die zweite Seite. |
| resultPdfPath | String | Der Pfad zur Zieldatei pdf. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wenn die zu vergleichenden Seiten unterschiedliche Größen haben. Wenn resultPdfPath null oder eine leere Zeichenfolge ist. |

### Siehe auch

* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [GraphicalPdfComparer](../)
* Namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument platziert.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page1 | Page | Die erste Seite. |
| page2 | Page | Die zweite Seite. |
| pdfDocument | Document | Die Instanz des PDF-Dokuments. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wenn die zu vergleichenden Seiten unterschiedliche Größen haben. |

### Siehe auch

* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [GraphicalPdfComparer](../)
* Namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../../)