---
title: MergeImages
second_title: Referencia de API de Aspose.PDF para .NET
description: Fusiona la lista de flujos de imágenes como un flujo de imágenes. Los formatos de salida png/jpg/tiff son compatibles en caso de utilizar un flujo de salida de formato no compatible codificado como Jpeg de forma predeterminada.
type: docs
weight: 180
url: /es/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## PdfConverter.MergeImages method

Fusiona la lista de flujos de imágenes como un flujo de imágenes. Los formatos de salida png/jpg/tiff son compatibles, en caso de utilizar un flujo de salida de formato no compatible codificado como Jpeg de forma predeterminada.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputImagesStreams | List`1 | La lista de secuencias de imágenes para fusionar. |
| outputImageFormat | ImageFormat | Formato de salida de imagen para transmisión fusionada. |
| mergeMode | ImageMergeMode | Modo de fusión. Se utiliza para formatos Png/Jpg. |
| horizontal | Nullable`1 | Relación horizontal para establecer el ancho del lienzo para el flujo de imágenes de salida. Se utiliza solo para formatos Png/Jpg con ImageMergeMode.Center. |
| vertical | Nullable`1 | Relación vertical para establecer la altura del lienzo para el flujo de imágenes de salida. Se utiliza solo para formatos Png/Jpg con ImageMergeMode.Center. |

### Valor_devuelto

Flujo de imágenes codificado como formato de imagen de salida.

### Ver también

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat)
* enum [ImageMergeMode](../../imagemergemode)
* class [PdfConverter](../../pdfconverter)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfconverter)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
