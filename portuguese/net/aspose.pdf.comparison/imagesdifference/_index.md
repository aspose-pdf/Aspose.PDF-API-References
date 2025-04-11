---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.ImagesDifference. Representa a classe de resultado da comparação de duas páginas PDF
type: docs
weight: 3230
url: /pt/net/aspose.pdf.comparison/imagesdifference/
---
## Classe ImagesDifference

Representa a classe de resultado da comparação de duas páginas PDF.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Obtém o array de diferença. Este array é semelhante ao array de dados da imagem original obtido como resultado do método LockBits. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | A altura da diferença. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Obtém a imagem da primeira página comparada. A imagem tem um formato de pixel de 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | O stride dos dados da imagem de diferença. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Converte o array de diferença em uma imagem bitmap usando as cores especificadas. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Realiza quaisquer operações de limpeza necessárias antes que o objeto seja destruído. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Retorna um novo bitmap representando a imagem de destino aplicando o array de diferença à imagem de origem. |

### Veja Também

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)