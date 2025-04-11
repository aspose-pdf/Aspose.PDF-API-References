---
title: GraphicalPdfComparer.CompareDocumentsToPdf
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicalPdfComparer. Compara documentos graficamente. O resultado da comparação é colocado em um documento PDF
type: docs
weight: 60
url: /pt/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/
---
## Método GraphicalPdfComparer.CompareDocumentsToPdf

Compara documentos graficamente. O resultado da comparação é colocado em um documento PDF.

```csharp
public void CompareDocumentsToPdf(Document document1, Document document2, string resultPdfPath)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document1 | Document | O primeiro documento a comparar. |
| document2 | Document | O segundo documento a comparar. |
| resultPdfPath | String | O caminho do arquivo pdf de destino. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | Se as páginas sendo comparadas tiverem tamanhos diferentes. Se resultPdfPath for nulo ou uma string vazia. |

### Veja Também

* classe [Document](../../../aspose.pdf/document/)
* classe [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)