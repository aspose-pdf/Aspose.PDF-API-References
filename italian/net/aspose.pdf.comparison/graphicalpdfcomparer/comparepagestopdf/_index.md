---
title: "GraphicalPdfComparer.ComparePagesToPdf"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo GraphicalPdfComparer. Confronta le pagine graficamente. Il risultato del confronto è collocato in un documento PDF"
type: docs
weight: 80
url: /it/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page1 | Page | La prima pagina. |
| page2 | Page | La seconda pagina. |
| resultPdfPath | String | Il percorso del file PDF di destinazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Se le pagine confrontate hanno dimensioni diverse. Se resultPdfPath è nullo o una stringa vuota. |

### Vedi anche

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page1 | Page | La prima pagina. |
| page2 | Page | La seconda pagina. |
| pdfDocument | Document | L'istanza del documento PDF. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Se le pagine confrontate hanno dimensioni diverse. |

### Vedi anche

* class [Page](../../../aspose.pdf/page/)
* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


