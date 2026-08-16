---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en jpeg."
type: docs
weight: 130
url: /es/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en jpeg.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [JpegDevice](#JpegDevice--) | Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima. |
| [JpegDevice](#JpegDevice-int-) | Inicializa una nueva instancia de la clase {@code JpegDevice}. |
| [JpegDevice](#JpegDevice-int-int-) | Inicializa una nueva instancia de la clase {@code JpegDevice} con dimensiones de imagen proporcionadas, resolución predeterminada (=150) y calidad máxima. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima. |

## Métodos

| Método | Descripción |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convierte la página a jpeg y la guarda en el flujo de salida. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convierte la página a jpeg y la guarda en el flujo de salida. |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima.

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

Inicializa una nueva instancia de la clase {@code JpegDevice}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| calidad |  | Especifica el nivel de compresión de una imagen. El rango de valores útiles para la calidad es de 0 a 100. Cuanto menor sea el número especificado, mayor será la compresión y, por lo tanto, menor la calidad de la imagen. Un cero produciría la imagen de menor calidad y 100 la de mayor calidad. |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

Inicializa una nueva instancia de la clase {@code JpegDevice} con dimensiones de imagen proporcionadas, resolución predeterminada (=150) y calidad máxima.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Ancho de salida de la imagen. |
| altura |  | Altura de salida de la imagen. |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima.

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
Inicializa una nueva instancia de la clase {@code JpegDevice} con resolución predeterminada y calidad máxima.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convierte la página a jpeg y la guarda en el flujo de salida.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Convierte la página a jpeg y la guarda en el flujo de salida.
