---
title: GraphicalPdfComparer.ComparePagesToPdf
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicalPdfComparer. Compara páginas graficamente. O resultado da comparação é colocado em um documento PDF
type: docs
weight: 80
url: /pt/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/
---
## ComparePagesToPdf(Page, Page, string) {#comparepagestopdf_1}

Compara páginas graficamente. O resultado da comparação é colocado em um documento PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, string resultPdfPath)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page1 | Page | A primeira página. |
| page2 | Page | A segunda página. |
| resultPdfPath | String | O caminho para o arquivo pdf de destino. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | Se as páginas sendo comparadas tiverem tamanhos diferentes. Se resultPdfPath for nulo ou uma string vazia. |

### Veja Também

* classe [Page](../../../aspose.pdf/page/)
* classe [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## ComparePagesToPdf(Page, Page, Document) {#comparepagestopdf}

Compara páginas graficamente. O resultado da comparação é colocado em um documento PDF.

```csharp
public void ComparePagesToPdf(Page page1, Page page2, Document pdfDocument)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page1 | Page | A primeira página. |
| page2 | Page | A segunda página. |
| pdfDocument | Document | A instância do documento pdf. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | Se as páginas sendo comparadas tiverem tamanhos diferentes. |

### Veja Também

* classe [Page](../../../aspose.pdf/page/)
* classe [Document](../../../aspose.pdf/document/)
* classe [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)