---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer-metod. Jämför två dokument sida för sida. Dokumenten jämförs som en helhet. Innan texten jämförs kombineras texterna från dokumentets sidor till en text
type: docs
weight: 50
url: /sv/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Jämför två dokument sida för sida. Dokumenten jämförs som en helhet. Innan texten jämförs kombineras texterna från dokumentets sidor till en text.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | Document | Första dokumentet. |
| document2 | Document | Andra dokumentet. |
| options | ComparisonOptions | Jämförelsealternativ. |

### Returvärde

Lista över ändringar.

### Se Även

* klass [DiffOperation](../../diffoperation/)
* klass [Document](../../../aspose.pdf/document/)
* klass [ComparisonOptions](../../comparisonoptions/)
* klass [TextPdfComparer](../)
* namnrymd [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Jämför två dokument sida för sida. Resultatet sparas i en PDF-fil. Dokumenten jämförs som en helhet. Innan texten jämförs kombineras texterna från dokumentets sidor till en text.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | Document | Första dokumentet. |
| document2 | Document | Andra dokumentet. |
| options | ComparisonOptions | Jämförelsealternativ. |
| resultPdfDocumentPath | String | Sökväg till pdf-filen för att spara jämförelse resultaten. |

### Returvärde

Lista över ändringar.

### Se Även

* klass [DiffOperation](../../diffoperation/)
* klass [Document](../../../aspose.pdf/document/)
* klass [ComparisonOptions](../../comparisonoptions/)
* klass [TextPdfComparer](../)
* namnrymd [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)