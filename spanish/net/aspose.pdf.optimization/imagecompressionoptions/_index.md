---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Optimization.ImageCompressionOptions. La clase contiene un conjunto de opciones para la compresión de imágenes
type: docs
weight: 7950
url: /es/net/aspose.pdf.optimization/imagecompressionoptions/
---
## Clase ImageCompressionOptions

La clase contiene un conjunto de opciones para la compresión de imágenes.

```csharp
public class ImageCompressionOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Si esta bandera se establece en verdadero, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Obtiene o establece la codificación utilizada para almacenar imágenes. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Especifica el nivel de compresión de la imagen cuando se utiliza la bandera CompressImages. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Especifica la resolución máxima de las imágenes. Si la imagen tiene una resolución más alta, se escalará. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Si esta bandera se establece en verdadero y CompressImages es verdadero, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Versión del algoritmo de compresión. Los valores posibles son: 1. compresión estándar, 2. rápida (compresión mejorada que es más rápida que la estándar pero puede no ser aplicable a todas las imágenes), 3. mixta (la compresión estándar se aplica a las imágenes que no se pueden comprimir con el algoritmo más rápido, esto puede dar la mejor compresión pero es más lento que el algoritmo "rápido". La versión "Rápida" no es aplicable para redimensionar imágenes (se utilizará el método estándar). El valor predeterminado es "Estándar". |

### Ver También

* espacio de nombres [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* ensamblaje [Aspose.PDF](../../)