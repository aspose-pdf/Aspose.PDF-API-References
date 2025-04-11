---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicalPdfComparer. Compara documentos graficamente. O resultado da comparação é colocado em imagens
type: docs
weight: 50
url: /pt/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## Método GraphicalPdfComparer.CompareDocumentsToImages

Compara documentos graficamente. O resultado da comparação é colocado em imagens.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document1 | Document | O primeiro documento a comparar. |
| document2 | Document | O segundo documento a comparar. |
| targetDirectory | String | O diretório para salvar os resultados da comparação. |
| fileNamePrefix | String | O prefixo do nome das imagens. |
| imageFormat | ImageFormat | O formato da imagem a ser salvo. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentException | Se as páginas sendo comparadas tiverem tamanhos diferentes. Se targetDirectory for nulo ou uma string vazia. Se fileNamePrefix for nulo ou uma string vazia. |

### Veja Também

* classe [Document](../../../aspose.pdf/document/)
* classe [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)