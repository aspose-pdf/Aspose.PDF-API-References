---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: Metodo TextPdfComparer. Confronta due documenti pagina per pagina
type: docs
weight: 40
url: /it/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

Confronta due documenti pagina per pagina.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document1 | Document | Primo documento.. |
| document2 | Document | Secondo documento. |
| options | ComparisonOptions | Opzioni di confronto. |

### Valore di Ritorno

Elenco delle modifiche per pagina.

### Vedi Anche

* classe [DiffOperation](../../diffoperation/)
* classe [Document](../../../aspose.pdf/document/)
* classe [ComparisonOptions](../../comparisonoptions/)
* classe [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Confronta due documenti pagina per pagina. Il risultato è salvato in un file PDF.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document1 | Document | Primo documento.. |
| document2 | Document | Secondo documento. |
| options | ComparisonOptions | Opzioni di confronto. |
| resultPdfDocumentPath | String | Percorso del file pdf per salvare i risultati del confronto. |

### Valore di Ritorno

Elenco delle modifiche per pagina.

### Vedi Anche

* classe [DiffOperation](../../diffoperation/)
* classe [Document](../../../aspose.pdf/document/)
* classe [ComparisonOptions](../../comparisonoptions/)
* classe [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)