---
title: ImageDevice
second_title: Referencia de API de Aspose.PDF para .NET
description: Una clase abstracta para dispositivos de imagen.
type: docs
weight: 1710
url: /es/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

Una clase abstracta para dispositivos de imagen.

```csharp
public abstract class ImageDevice : PageDevice
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageDevice](imagedevice#constructor)() | Inicializador abstracto para[`ImageDevice`](../imagedevice) descendientes, establezca la resolución en 150x150. |
| [ImageDevice](imagedevice#constructor_2)(PageSize) | Inicializa una nueva instancia del[`JpegDevice`](../jpegdevice) clase con dimensiones de imagen proporcionadas y resolución predeterminada (=150). |
| [ImageDevice](imagedevice#constructor_1)(Resolution) | Inicializador abstracto para[`ImageDevice`](../imagedevice) descendientes.  Resolución para el archivo de imagen de resultado, consulte[`Resolution`](./resolution) clase. |
| [ImageDevice](imagedevice#constructor_4)(int, int) | Inicializa una nueva instancia del[`JpegDevice`](../jpegdevice) clase con dimensiones de imagen proporcionadas y resolución predeterminada (=150). |
| [ImageDevice](imagedevice#constructor_3)(PageSize, Resolution) | Inicializa una nueva instancia del[`JpegDevice`](../jpegdevice) clase con dimensiones de imagen y resolución proporcionadas. |
| [ImageDevice](imagedevice#constructor_5)(int, int, Resolution) | Inicializa una nueva instancia del[`JpegDevice`](../jpegdevice) clase con dimensiones de imagen y resolución proporcionadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype) { get; set; } | Obtiene o establece el tipo de coordenada de la página (Medios/Cuadros de recorte). El valor de CropBox se usa por defecto. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode) { get; set; } | Obtiene o establece el modo de presentación del formulario. |
| [Height](../../aspose.pdf.devices/imagedevice/height) { get; } | Obtiene la altura de salida de la imagen. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions) { get; set; } | Obtiene o establece las opciones de representación. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution) { get; } | Obtiene la resolución de la imagen. |
| [Width](../../aspose.pdf.devices/imagedevice/width) { get; } | Obtiene el ancho de salida de la imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process)(Page, Stream) | Realiza alguna operación en la página dada, por ejemplo, convierte la página en una imagen gráfica. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |

### Ver también

* class [PageDevice](../pagedevice)
* espacio de nombres [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->