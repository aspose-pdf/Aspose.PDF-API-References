---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Optimization.ImageCompressionOptions. A classe contém um conjunto de opções para compressão de imagem
type: docs
weight: 7950
url: /pt/net/aspose.pdf.optimization/imagecompressionoptions/
---
## Classe ImageCompressionOptions

A classe contém um conjunto de opções para compressão de imagem.

```csharp
public class ImageCompressionOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Se esta flag estiver definida como verdadeira, as imagens serão comprimidas no documento. O nível de compressão é especificado pela propriedade ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Obtém ou define a codificação usada para armazenar imagens. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Especifica o nível de compressão da imagem quando a flag CompressImages é usada. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Especifica a resolução máxima das imagens. Se a imagem tiver uma resolução mais alta, ela será redimensionada. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Se esta flag estiver definida como verdadeira e CompressImages for verdadeira, as imagens serão redimensionadas se a resolução da imagem for maior que o parâmetro MaxResolution especificado. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Versão do algoritmo de compressão. Os valores possíveis são: 1. compressão padrão, 2. rápida (compressão melhorada que é mais rápida que a padrão, mas pode não ser aplicável a todas as imagens), 3. mista (compressão padrão é aplicada a imagens que não podem ser comprimidas pelo algoritmo mais rápido, isso pode oferecer a melhor compressão, mas é mais lenta que o algoritmo "rápido". A versão "Rápida" não é aplicável para redimensionar imagens (o método padrão será usado). O padrão é "Padrão". |

### Veja Também

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)