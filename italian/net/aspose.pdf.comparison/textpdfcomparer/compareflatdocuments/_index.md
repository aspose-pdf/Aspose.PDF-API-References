---
title: "TextPdfComparer.CompareFlatDocuments"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo TextPdfComparer. Confronta due documenti pagina per pagina. I documenti sono confrontati nel loro insieme. Prima di confrontare il testo, i testi delle pagine del documento sono combinati in un unico testo"
type: docs
weight: 50
url: /it/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

Confronta due documenti pagina per pagina. I documenti vengono confrontati nel loro complesso. Prima di confrontare il testo, i testi delle pagine del documento vengono combinati in un unico testo.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document1 | Document | Primo documento. |
| document2 | Document | Secondo documento. |
| options | ComparisonOptions | Opzioni di confronto. |

### Valore di ritorno

Elenco delle modifiche.

### Vedi anche

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

Confronta due documenti pagina per pagina. Il risultato viene salvato in un file PDF. I documenti vengono confrontati nel loro complesso. Prima di confrontare il testo, i testi delle pagine del documento vengono combinati in un unico testo.

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document1 | Document | Primo documento. |
| document2 | Document | Secondo documento. |
| options | ComparisonOptions | Opzioni di confronto. |
| resultPdfDocumentPath | String | Percorso del file pdf in cui salvare i risultati del confronto. |

### Valore di ritorno

Elenco delle modifiche.

### Vedi anche

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


