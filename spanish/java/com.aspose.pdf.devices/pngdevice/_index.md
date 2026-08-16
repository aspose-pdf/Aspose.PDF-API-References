---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en png."
type: docs
weight: 160
url: /es/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en png.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PngDevice](#PngDevice--) | Inicializa una nueva instancia de la clase {@code PngDevice} con resolución predeterminada. |
| [PngDevice](#PngDevice-int-int-) | Inicializa una nueva instancia de la clase {@code PngDevice} con dimensiones de imagen proporcionadas, resolución predeterminada (=150). |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code PngDevice} con resolución predeterminada. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | Inicializa una nueva instancia de la clase {@code PngDevice} con resolución predeterminada. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code PngDevice} con resolución predeterminada. |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code PngDevice} con resolución predeterminada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | Obtiene o establece si la imagen tiene fondo transparente. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convierte la página a png y la guarda en el flujo de salida. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convierte la página a png y la guarda en el flujo de salida. |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | Convierte la página en BufferedImage. |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Convierte la página en BufferedImage con binarización Bradley. |
| [setTransparentBackground](#setTransparentBackground-boolean-) | Obtiene o establece si la imagen tiene fondo transparente. |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

Inicializa una nueva instancia de la clase {@code PngDevice} con resolución predeterminada.

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

Inicializa una nueva instancia de la clase {@code PngDevice} con dimensiones de imagen proporcionadas, resolución predeterminada (=150).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Ancho de salida de la imagen. |
| altura |  | Altura de salida de la imagen. |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code PngDevice} con resolución predeterminada.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
Inicializa una nueva instancia de la clase {@code PngDevice} con resolución predeterminada.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code PngDevice} con resolución predeterminada.

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code PngDevice} con resolución predeterminada.

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

Obtiene o establece si la imagen tiene fondo transparente.

**Returns:**
valor booleano

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convierte la página a png y la guarda en el flujo de salida.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Convierte la página a png y la guarda en el flujo de salida.

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
Convierte la página en BufferedImage.

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
Convierte la página en BufferedImage con binarización Bradley.

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

Obtiene o establece si la imagen tiene fondo transparente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
