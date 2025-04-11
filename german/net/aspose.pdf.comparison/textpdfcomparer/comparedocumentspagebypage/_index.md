---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer-Methode. Vergleicht zwei Dokumente seitenweise
type: docs
weight: 40
url: /de/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

Vergleicht zwei Dokumente seitenweise.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document1 | Document | Erstes Dokument.. |
| document2 | Document | Zweites Dokument. |
| options | ComparisonOptions | Vergleichsoptionen. |

### Rückgabewert

Liste der Änderungen nach Seite.

### Siehe auch

* Klasse [DiffOperation](../../diffoperation/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [ComparisonOptions](../../comparisonoptions/)
* Klasse [TextPdfComparer](../)
* Namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Vergleicht zwei Dokumente seitenweise. Das Ergebnis wird in einer PDF-Datei gespeichert.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document1 | Document | Erstes Dokument.. |
| document2 | Document | Zweites Dokument. |
| options | ComparisonOptions | Vergleichsoptionen. |
| resultPdfDocumentPath | String | Pfad zur PDF-Datei, um die Vergleichsergebnisse zu speichern. |

### Rückgabewert

Liste der Änderungen nach Seite.

### Siehe auch

* Klasse [DiffOperation](../../diffoperation/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [ComparisonOptions](../../comparisonoptions/)
* Klasse [TextPdfComparer](../)
* Namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../../)