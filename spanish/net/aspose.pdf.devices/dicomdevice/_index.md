---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Devices.DicomDevice. Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en formato Dicom
type: docs
weight: 3560
url: /es/net/aspose.pdf.devices/dicomdevice/
---
## Clase DicomDevice

Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en formato Dicom.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Inicializa una nueva instancia de la clase `DicomDevice` con resolución predeterminada. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Inicializa una nueva instancia de la clase `DicomDevice` con el tamaño de página proporcionado, con resolución predeterminada (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Inicializa una nueva instancia de la clase `DicomDevice`. Resolución para el archivo de imagen resultante, ver clase [`Resolution`](../resolution/). |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Inicializa una nueva instancia de la clase `DicomDevice` con las dimensiones de imagen proporcionadas, con resolución predeterminada (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Inicializa una nueva instancia de la clase `DicomDevice` con el tamaño de página y la resolución proporcionados. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Inicializa una nueva instancia de la clase `DicomDevice` con las dimensiones de imagen y la resolución proporcionadas. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Convierte la página en Dicom y la guarda en el flujo de salida. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |

### Véase también

* clase [ImageDevice](../imagedevice/)
* espacio de nombres [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* ensamblaje [Aspose.PDF](../../)