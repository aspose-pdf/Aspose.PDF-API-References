---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.ImagePlacement. Representa las características de una imagen colocada en la página del documento Pdf
type: docs
weight: 5900
url: /es/net/aspose.pdf/imageplacement/
---
## Clase ImagePlacement

Representa las características de una imagen colocada en la página del documento Pdf.

```csharp
public sealed class ImagePlacement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Obtiene los parámetros de composición del estado gráfico activo para la imagen colocada en la página. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Obtiene el objeto de recurso XImage relacionado. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Matriz de transformación actual para esta imagen. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Operador utilizado para mostrar la imagen. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Obtiene la página que contiene la imagen. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Obtiene el rectángulo de la imagen. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Obtiene la resolución de la imagen. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Obtiene el ángulo de rotación de la imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Elimina la imagen de la página. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Reemplaza la imagen en la colección con otra imagen. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Guarda la imagen con las transformaciones correspondientes: escalado, rotación y resolución. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Guarda la imagen con las transformaciones correspondientes: escalado, rotación y resolución. |

## Observaciones

Cuando una imagen se coloca en una página, puede tener dimensiones diferentes a las dimensiones físicas definidas en [`Resources`](../resources/). El objeto `ImagePlacement` está destinado a proporcionar información como dimensiones, resolución, etc.

## Ejemplos

El ejemplo demuestra cómo encontrar imágenes en la primera página del documento PDF y obtener imágenes como mapas de bits con dimensiones visibles.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Véase También

* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)