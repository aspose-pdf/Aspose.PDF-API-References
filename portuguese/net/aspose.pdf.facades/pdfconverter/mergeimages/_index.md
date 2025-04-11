---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: Método PdfConverter. Mescla uma lista de fluxos de imagem em um único fluxo de imagem. Formatos de saída Png/jpg/tiff são suportados, caso um fluxo de saída em formato não suportado seja codificado como Jpeg por padrão.
type: docs
weight: 180
url: /pt/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## Método PdfConverter.MergeImages

Mescla uma lista de fluxos de imagem em um único fluxo de imagem. Formatos de saída Png/jpg/tiff são suportados, caso um fluxo de saída em formato não suportado seja codificado como Jpeg por padrão.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputImagesStreams | List`1 | A lista de fluxos de imagem a serem mesclados. |
| outputImageFormat | ImageFormat | Formato de saída da imagem para o fluxo mesclado. |
| mergeMode | ImageMergeMode | Modo de mesclagem. Usado para formatos Png/Jpg. |
| horizontal | Nullable`1 | Razão horizontal para definir a largura da tela para o fluxo de imagem de saída. Usado apenas para formatos Png/Jpg com ImageMergeMode.Center. |
| vertical | Nullable`1 | Razão vertical para definir a altura da tela para o fluxo de imagem de saída. Usado apenas para formatos Png/Jpg com ImageMergeMode.Center. |

### Valor de Retorno

Fluxo de imagem codificado como formato de imagem de saída.

### Veja Também

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)