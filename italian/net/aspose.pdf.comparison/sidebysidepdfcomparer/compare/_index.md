---
title: "SideBySidePdfComparer.Compare"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo SideBySidePdfComparer. Confronta due pagine. Il risultato è salvato in un documento PDF in cui la prima pagina è scritta per prima e poi la seconda. Puoi aprirlo in Adobe Acrobat nella visualizzazione a due pagine per vedere le modifiche affiancate. Le eliminazioni sono annotate sulla pagina sinistra e le inserzioni sulla pagina destra."
type: docs
weight: 10
url: /it/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

Confronta due pagine. Il risultato viene salvato in un documento PDF in cui la prima pagina è scritta per prima, seguita dalla seconda. È possibile aprirlo in Adobe Acrobat in visualizzazione a due pagine per vedere le modifiche affiancate. Le eliminazioni sono annotate sulla pagina a sinistra, e le inserzioni sono annotate sulla pagina a destra.

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page1 | Page | La prima pagina da confrontare. |
| page2 | Page | La prima pagina da confrontare. |
| targetPdfPath | String | Il percorso al file PDF per salvare il risultato del confronto. |
| options | SideBySideComparisonOptions | Le opzioni di confronto. |

### Vedi anche

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

Confronta due documenti. Le pagine sono confrontate una per una. Le pagine dei documenti confrontati vengono copiate una dopo l'altra nel documento risultante. Prima la prima pagina del primo documento, poi la prima pagina del secondo documento. Successivamente la seconda pagina del primo documento e poi la seconda pagina del secondo documento, ecc. È possibile aprirlo in Adobe Acrobat in visualizzazione a due pagine per vedere le modifiche affiancate. Le eliminazioni sono annotate sulla pagina a sinistra, e le inserzioni sono annotate sulla pagina a destra.

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document1 | Document | Il primo documento da confrontare. |
| document2 | Document | Il secondo documento da confrontare. |
| targetPdfPath | String | Il percorso al file PDF per salvare il risultato del confronto. |
| options | SideBySideComparisonOptions | Le opzioni di confronto. |

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


