---
title: Class DocumentDevice
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Devices.DocumentDevice. Clase abstracta para todos los dispositivos que se utilizan para procesar todo el documento pdf
type: docs
weight: 3570
url: /es/net/aspose.pdf.devices/documentdevice/
---
## Clase DocumentDevice

Clase abstracta para todos los dispositivos que se utilizan para procesar todo el documento pdf.

```csharp
public abstract class DocumentDevice : PageDevice
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | Procesa todo el documento y guarda los resultados en el flujo. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | Procesa todo el documento y guarda los resultados en el archivo. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Realiza alguna operación en la página dada, por ejemplo, convierte la página en una imagen gráfica. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | Cada dispositivo representa alguna operación en el documento, por ejemplo, podemos convertir el documento pdf a otro formato. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | Procesa ciertas páginas del documento y guarda los resultados en el archivo. |

### Ver También

* clase [PageDevice](../pagedevice/)
* espacio de nombres [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* ensamblaje [Aspose.PDF](../../)