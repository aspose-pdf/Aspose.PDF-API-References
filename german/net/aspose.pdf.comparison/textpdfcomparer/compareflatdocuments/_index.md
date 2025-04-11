---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer-Methode. Vergleicht zwei Dokumente seitenweise. Die Dokumente werden als Ganzes verglichen. Vor dem Vergleich von Text werden die Texte der Dokumentseiten zu einem Text kombiniert.
type: docs
weight: 50
url: /de/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Vergleicht zwei Dokumente seitenweise. Die Dokumente werden als Ganzes verglichen. Vor dem Vergleich von Text werden die Texte der Dokumentseiten zu einem Text kombiniert.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document1 | Document | Erstes Dokument. |
| document2 | Document | Zweites Dokument. |
| options | ComparisonOptions | Vergleichsoptionen. |

### Rückgabewert

Liste der Änderungen.

### Siehe auch

* Klasse [DiffOperation](../../diffoperation/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [ComparisonOptions](../../comparisonoptions/)
* Klasse [TextPdfComparer](../)
* Namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Vergleicht zwei Dokumente seitenweise. Das Ergebnis wird in einer PDF-Datei gespeichert. Die Dokumente werden als Ganzes verglichen. Vor dem Vergleich von Text werden die Texte der Dokumentseiten zu einem Text kombiniert.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document1 | Document | Erstes Dokument. |
| document2 | Document | Zweites Dokument. |
| options | ComparisonOptions | Vergleichsoptionen. |
| resultPdfDocumentPath | String | Pfad zur PDF-Datei, um die Vergleichsergebnisse zu speichern. |

### Rückgabewert

Liste der Änderungen.

### Siehe auch

* Klasse [DiffOperation](../../diffoperation/)
* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [ComparisonOptions](../../comparisonoptions/)
* Klasse [TextPdfComparer](../)
* Namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../../)