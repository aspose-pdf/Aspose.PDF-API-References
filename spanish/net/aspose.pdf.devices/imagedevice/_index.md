---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Devices.ImageDevice. Una clase abstracta para dispositivos de imagen
type: docs
weight: 3610
url: /es/net/aspose.pdf.devices/imagedevice/
---
## Clase ImageDevice

Una clase abstracta para dispositivos de imagen.

```csharp
public abstract class ImageDevice : PageDevice
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Inicializador abstracto para descendientes de `ImageDevice`, establece la resolución en 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Inicializa una nueva instancia de la clase [`JpegDevice`](../jpegdevice/) con las dimensiones de imagen proporcionadas y la resolución predeterminada (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Inicializador abstracto para descendientes de `ImageDevice`. Resolución para el archivo de imagen resultante, ver clase [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Inicializa una nueva instancia de la clase [`JpegDevice`](../jpegdevice/) con las dimensiones de imagen proporcionadas y la resolución predeterminada (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Inicializa una nueva instancia de la clase [`JpegDevice`](../jpegdevice/) con las dimensiones de imagen proporcionadas y la resolución. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Inicializa una nueva instancia de la clase [`JpegDevice`](../jpegdevice/) con las dimensiones de imagen proporcionadas y la resolución. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Realiza alguna operación en la página dada, por ejemplo, convierte la página en una imagen gráfica. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |

### Véase también

* clase [PageDevice](../pagedevice/)
* espacio de nombres [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* ensamblaje [Aspose.PDF](../../)