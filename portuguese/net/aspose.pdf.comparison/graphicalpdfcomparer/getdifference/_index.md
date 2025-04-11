---
title: GraphicalPdfComparer.GetDifference
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicalPdfComparer. Obtém diferenças entre imagens de páginas. O resultado contém uma imagem da primeira página comparada e um array de diferenças
type: docs
weight: 90
url: /pt/net/aspose.pdf.comparison/graphicalpdfcomparer/getdifference/
---
## Método GraphicalPdfComparer.GetDifference

Obtém diferenças entre imagens de páginas. O resultado contém uma imagem da primeira página comparada e um array de diferenças.

```csharp
public ImagesDifference GetDifference(Page page1, Page page2)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page1 | Page | A primeira página. |
| page2 | Page | A segunda página. |

### Valor de Retorno

A instância de [`ImagesDifference`](../../imagesdifference/).

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | Se as páginas sendo comparadas tiverem tamanhos diferentes. |

### Veja Também

* classe [ImagesDifference](../../imagesdifference/)
* classe [Page](../../../aspose.pdf/page/)
* classe [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)