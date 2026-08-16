---
title: "ThumbnailDevice"
linktitle: "ThumbnailDevice"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un dispositivo de imagen que guarda las páginas del documento pdf en una imagen en miniatura."
type: docs
weight: 200
url: /es/java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.ThumbnailDevice

```
public final class ThumbnailDevice extends ImageDevice
```

Representa un dispositivo de imagen que guarda las páginas del documento pdf en una imagen en miniatura.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ThumbnailDevice](#ThumbnailDevice--) | Inicializa una nueva instancia de la clase {@link ThumbnailDevice} con el tamaño predeterminado de la imagen miniatura (200x200 píxeles). |
| [ThumbnailDevice](#ThumbnailDevice-int-int-) | Inicializa una nueva instancia de la clase {@link ThumbnailDevice}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [processInternal](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | Convierte la página a una imagen miniatura png y la guarda en el flujo de salida. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Realiza alguna operación en la página dada, p. ej. |

### ThumbnailDevice {#ThumbnailDevice--}
```
public ThumbnailDevice()
```

Inicializa una nueva instancia de la clase {@link ThumbnailDevice} con el tamaño predeterminado de la imagen miniatura (200x200 píxeles).

### ThumbnailDevice {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```

Inicializa una nueva instancia de la clase {@link ThumbnailDevice}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Ancho de salida de la imagen miniatura. |
| altura |  | Altura de salida de la imagen miniatura. |

### processInternal {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
Convierte la página a una imagen miniatura png y la guarda en el flujo de salida.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Realiza alguna operación en la página dada, p. ej.
