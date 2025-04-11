---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Comparison.ImagesDifference. Representa la clase de resultado de comparar dos páginas PDF
type: docs
weight: 3230
url: /es/net/aspose.pdf.comparison/imagesdifference/
---
## Clase ImagesDifference

Representa la clase de resultado de comparar dos páginas PDF.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Obtiene el array de diferencias. Este array es similar al array de datos de imagen original obtenido como resultado del método LockBits. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | La altura de la diferencia. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Obtiene la imagen de la primera página comparada. La imagen tiene un formato de píxel de 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | El stride de los datos de imagen de diferencia. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Convierte el array de diferencias a una imagen bitmap utilizando los colores especificados. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Realiza cualquier operación de limpieza necesaria antes de que el objeto sea destruido. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Devuelve un nuevo bitmap que representa la imagen de destino aplicando el array de diferencias a la imagen de origen. |

### Ver También

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)