---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Devices.ThumbnailDevice. Representa un dispositivo de imagen que guarda las páginas del documento pdf en una imagen en miniatura.
type: docs
weight: 3690
url: /es/net/aspose.pdf.devices/thumbnaildevice/
---
## Clase ThumbnailDevice

Representa un dispositivo de imagen que guarda las páginas del documento pdf en una imagen en miniatura.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Inicializa una nueva instancia de la clase `ThumbnailDevice` con el tamaño predeterminado de la imagen en miniatura (200x200 píxeles). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Inicializa una nueva instancia de la clase `ThumbnailDevice`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtiene o establece el tipo de coordenadas de la página (cajas Media/Crop). El valor CropBox se utiliza por defecto. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtiene o establece el modo de presentación del formulario. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtiene la altura de salida de la imagen. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtiene o establece las opciones de renderizado. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtiene la resolución de la imagen. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtiene el ancho de salida de la imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Convierte la página en una imagen en miniatura png y la guarda en el flujo de salida. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |

### Ver También

* clase [ImageDevice](../imagedevice/)
* espacio de nombres [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* ensamblaje [Aspose.PDF](../../)