---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: Metodo SideBySidePdfComparer. Confronta due pagine. Il risultato è salvato in un documento PDF in cui la prima pagina è scritta per prima e poi la seconda. Puoi aprirlo in Adobe Acrobat in modalità Due pagine per vedere le modifiche affiancate. Le cancellazioni sono annotate sulla pagina a sinistra e le inserzioni sono annotate sulla pagina a destra.
type: docs
weight: 10
url: /it/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Confronta due pagine. Il risultato è salvato in un documento PDF in cui la prima pagina è scritta per prima, e poi la seconda. Puoi aprirlo in Adobe Acrobat in modalità Due pagine per vedere le modifiche affiancate. Le cancellazioni sono annotate sulla pagina a sinistra, e le inserzioni sono annotate sulla pagina a destra.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | La prima pagina da confrontare. |
| page2 | Page | La seconda pagina da confrontare. |
| targetPdfPath | String | Il percorso del file PDF in cui salvare il risultato del confronto. |
| options | SideBySideComparisonOptions | Le opzioni di confronto. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Confronta due documenti. Le pagine vengono confrontate una per una. Le pagine dei documenti confrontati vengono copiate una dopo l'altra nel documento risultante. Prima la prima pagina del primo documento, poi la prima pagina del secondo documento. Successivamente la seconda del primo documento e poi la seconda del secondo documento, ecc. Puoi aprirlo in Adobe Acrobat in modalità Due pagine per vedere le modifiche affiancate. Le cancellazioni sono annotate sulla pagina a sinistra, e le inserzioni sono annotate sulla pagina a destra.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | Il primo documento da confrontare. |
| document2 | Document | Il secondo documento da confrontare. |
| targetPdfPath | String | Il percorso del file PDF in cui salvare il risultato del confronto. |
| options | SideBySideComparisonOptions | Le opzioni di confronto. |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)