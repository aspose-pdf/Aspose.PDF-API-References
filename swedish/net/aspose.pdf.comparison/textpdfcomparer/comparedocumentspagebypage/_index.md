---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer metod. Jämför två dokument sida för sida
type: docs
weight: 40
url: /sv/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

Jämför två dokument sida för sida.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | Document | Första dokumentet.. |
| document2 | Document | Andra dokumentet. |
| options | ComparisonOptions | Jämförelsealternativ. |

### Returvärde

Lista över ändringar per sida.

### Se Även

* klass [DiffOperation](../../diffoperation/)
* klass [Document](../../../aspose.pdf/document/)
* klass [ComparisonOptions](../../comparisonoptions/)
* klass [TextPdfComparer](../)
* namnrymd [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Jämför två dokument sida för sida. Resultatet sparas i en PDF-fil.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | Document | Första dokumentet.. |
| document2 | Document | Andra dokumentet. |
| options | ComparisonOptions | Jämförelsealternativ. |
| resultPdfDocumentPath | String | Sökväg till pdf-filen för att spara jämförelseresultaten. |

### Returvärde

Lista över ändringar per sida.

### Se Även

* klass [DiffOperation](../../diffoperation/)
* klass [Document](../../../aspose.pdf/document/)
* klass [ComparisonOptions](../../comparisonoptions/)
* klass [TextPdfComparer](../)
* namnrymd [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)