---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: Método PdfConverter. Combina una lista de flujos de imágenes en un solo flujo de imagen. Se admiten formatos de salida Png/jpg/tiff en caso de usar un flujo de salida de formato no soportado codificado como Jpeg por defecto.
type: docs
weight: 180
url: /es/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## Método PdfConverter.MergeImages

Combina una lista de flujos de imágenes en un solo flujo de imagen. Se admiten formatos de salida Png/jpg/tiff, en caso de usar un flujo de salida de formato no soportado codificado como Jpeg por defecto.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputImagesStreams | List`1 | La lista de flujos de imágenes a combinar. |
| outputImageFormat | ImageFormat | Formato de salida de imagen para el flujo combinado. |
| mergeMode | ImageMergeMode | Modo de combinación. Usado para formatos Png/Jpg. |
| horizontal | Nullable`1 | Proporción horizontal para establecer el ancho del lienzo para el flujo de imagen de salida. Usado para formatos Png/Jpg con ImageMergeMode.Center solamente. |
| vertical | Nullable`1 | Proporción vertical para establecer la altura del lienzo para el flujo de imagen de salida. Usado para formatos Png/Jpg con ImageMergeMode.Center solamente. |

### Valor de Retorno

Flujo de imagen codificado como formato de imagen de salida.

### Véase También

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)