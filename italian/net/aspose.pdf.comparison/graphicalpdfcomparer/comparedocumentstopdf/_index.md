---
title: GraphicalPdfComparer.CompareDocumentsToPdf
second_title: Aspose.PDF for .NET API Reference
description: Il risultato della comparazione viene inserito in un documento PDF.
type: docs
weight: 60
url: /it/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/
---
## Metodo GraphicalPdfComparer.CompareDocumentsToPdf

Confronta i documenti graficamente. Il risultato del confronto è inserito in un documento PDF.

```csharp
public void CompareDocumentsToPdf(Document document1, Document document2, string resultPdfPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document1 | Document | Il primo documento da confrontare. |
| document2 | Document | Il secondo documento da confrontare. |
| resultPdfPath | String | Il percorso del file pdf di destinazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Se le pagine da confrontare sono di dimensioni diverse. Se resultPdfPath è nullo o una stringa vuota. |

### Vedi Anche

* classe [Document](../../../aspose.pdf/document/)
* classe [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)