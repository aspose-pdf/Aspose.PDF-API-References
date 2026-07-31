---
title: "TextPdfComparer.CompareDocumentsPageByPage"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo TextPdfComparer. Confronta due documenti pagina per pagina"
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

### Valore di ritorno

Elenco delle modifiche per pagina.

### Vedi anche

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

Confronta due documenti pagina per pagina. Il risultato viene salvato in un file PDF.

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document1 | Document | Primo documento.. |
| document2 | Document | Secondo documento. |
| options | ComparisonOptions | Opzioni di confronto. |
| resultPdfDocumentPath | String | Percorso del file pdf in cui salvare i risultati del confronto. |

### Valore di ritorno

Elenco delle modifiche per pagina.

### Vedi anche

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


