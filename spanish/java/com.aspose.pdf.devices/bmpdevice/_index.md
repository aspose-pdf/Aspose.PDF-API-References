---
title: "BmpDevice"
linktitle: "BmpDevice"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en bmp."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en bmp.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [BmpDevice](#BmpDevice--) | Inicializa una nueva instancia de la clase {@code BmpDevice} con resolución predeterminada. |
| [BmpDevice](#BmpDevice-int-int-) | Inicializa una nueva instancia de la clase {@code BmpDevice} con dimensiones de imagen proporcionadas, resolución predeterminada (=150). |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code BmpDevice} con resolución predeterminada. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | Inicializa una nueva instancia de la clase {@code BmpDevice} con resolución predeterminada. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code BmpDevice} con resolución predeterminada. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code BmpDevice} con resolución predeterminada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | renderiza la página en los gráficos |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convierte la página a bmp y la guarda en el flujo de salida. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | ¡Solo para uso interno! |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

Inicializa una nueva instancia de la clase {@code BmpDevice} con resolución predeterminada.

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

Inicializa una nueva instancia de la clase {@code BmpDevice} con dimensiones de imagen proporcionadas, resolución predeterminada (=150).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Ancho de salida de la imagen. |
| altura |  | Altura de salida de la imagen. |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code BmpDevice} con resolución predeterminada.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
Inicializa una nueva instancia de la clase {@code BmpDevice} con resolución predeterminada.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code BmpDevice} con resolución predeterminada.

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code BmpDevice} con resolución predeterminada.

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
renderiza la página en los gráficos

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convierte la página a bmp y la guarda en el flujo de salida.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
¡Solo para uso interno!
