---
title: GraphicalPdfComparer.ComparePagesToImage
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicalPdfComparer. Compara páginas graficamente. O resultado da comparação é colocado em uma imagem
type: docs
weight: 70
url: /pt/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## Método GraphicalPdfComparer.ComparePagesToImage

Compara páginas graficamente. O resultado da comparação é colocado em uma imagem.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page1 | Page | A primeira página a ser comparada. |
| page2 | Page | A segunda página a ser comparada. |
| resultImagePath | String | O caminho para o arquivo de imagem de destino. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | Se as páginas sendo comparadas tiverem tamanhos diferentes. Se resultImagePath for nulo ou uma string vazia. Há um formato de imagem desconhecido para salvar. |

### Veja Também

* classe [Page](../../../aspose.pdf/page/)
* classe [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)