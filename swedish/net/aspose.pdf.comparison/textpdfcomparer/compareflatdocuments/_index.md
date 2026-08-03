---
title: "TextPdfComparer.CompareFlatDocuments"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextPdfComparer-metod. Jämför två dokument sida för sida. Dokumenten jämförs som en helhet. Innan text jämförs kombineras texterna från dokumentens sidor till en enda text."
type: docs
weight: 50
url: /sv/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Jämför två dokument sida för sida. Dokumenten jämförs som helhet. Innan text jämförs kombineras texterna på dokumentens sidor till en enda text.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | Dokument | Första dokumentet. |
| document2 | Dokument | Andra dokumentet. |
| options | ComparisonOptions | Jämförelsealternativ. |

### Returvärde

Lista över ändringar.

### Se även

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Jämför två dokument sida för sida. Resultatet sparas i en PDF-fil. Dokumenten jämförs som helhet. Innan text jämförs kombineras texterna på dokumentens sidor till en enda text.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document1 | Dokument | Första dokumentet. |
| document2 | Dokument | Andra dokumentet. |
| options | ComparisonOptions | Jämförelsealternativ. |
| resultPdfDocumentPath | String | Sökväg till pdf-filen för att spara jämförelsens resultat. |

### Returvärde

Lista över ändringar.

### Se även

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


