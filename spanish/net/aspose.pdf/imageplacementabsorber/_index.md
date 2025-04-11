---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.ImagePlacementAbsorber. Representa un objeto absorbente de objetos de colocación de imágenes. Realiza la búsqueda de usos de imágenes y proporciona acceso a los resultados de búsqueda a través de la colección ImagePlacements.
type: docs
weight: 5910
url: /es/net/aspose.pdf/imageplacementabsorber/
---
## Clase ImagePlacementAbsorber

Representa un objeto absorbente de objetos de colocación de imágenes. Realiza la búsqueda de usos de imágenes y proporciona acceso a los resultados de búsqueda a través de la colección [`ImagePlacements`](./imageplacements/).

```csharp
public sealed class ImagePlacementAbsorber
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Obtiene la colección de ocurrencias de colocación de imágenes que se presentan con objetos [`ImagePlacement`](../imageplacement/). |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Obtiene/establece el modo de solo lectura para la colección de operaciones de análisis. Puede ayudar contra excepciones de falta de memoria. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Realiza la búsqueda en el documento especificado. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Realiza la búsqueda en la página especificada. |

## Observaciones

El objeto `ImagePlacementAbsorber` se utiliza básicamente en el escenario de búsqueda de imágenes. Cuando se completa la búsqueda, las ocurrencias se representan con objetos [`ImagePlacement`](../imageplacement/) que contiene la colección [`ImagePlacements`](./imageplacements/). El objeto [`ImagePlacement`](../imageplacement/) proporciona acceso a las propiedades de colocación de imágenes: dimensiones, resolución, etc. La rotación positiva de la imagen es en sentido antihorario, para la página, es en sentido horario. Aquí, necesitamos representar el ángulo de rotación de la imagen, por lo que deducimos el ángulo de la página del ángulo de la imagen.

## Ejemplos

El ejemplo demuestra cómo encontrar imágenes en la primera página del documento PDF y obtener las propiedades de colocación de la imagen.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### Véase también

* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)