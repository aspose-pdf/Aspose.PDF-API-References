---
title: "EmfDevice"
linktitle: "EmfDevice"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en emf."
type: docs
weight: 70
url: /es/java/com.aspose.pdf.devices/emfdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.EmfDevice

```
public final class EmfDevice extends ImageDevice
```

Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en emf.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfDevice](#EmfDevice--) | Inicializa una nueva instancia de la clase {@code EmfDevice} con la resolución predeterminada de la imagen raster escrita en emf. |
| [EmfDevice](#EmfDevice-int-int-) | Inicializa una nueva instancia de la clase {@code EmfDevice} con las dimensiones de imagen proporcionadas y la resolución predeterminada para la imagen raster escrita en emf (=150). |
| [EmfDevice](#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code EmfDevice} con la resolución predeterminada de la imagen raster escrita en emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-) | Inicializa una nueva instancia de la clase {@code EmfDevice} con la resolución predeterminada de la imagen raster escrita en emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code EmfDevice} con la resolución predeterminada de la imagen raster escrita en emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@code EmfDevice} con la resolución predeterminada de la imagen raster escrita en emf. |

## Métodos

| Método | Descripción |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convierte la página a emf y la guarda en el flujo de salida. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convierte la página a emf y la guarda en el flujo de salida. |

### EmfDevice {#EmfDevice--}
```
public EmfDevice()
```

Inicializa una nueva instancia de la clase {@code EmfDevice} con la resolución predeterminada de la imagen raster escrita en emf.

### EmfDevice {#EmfDevice-int-int-}
```
public EmfDevice(int width, int height)
```

Inicializa una nueva instancia de la clase {@code EmfDevice} con las dimensiones de imagen proporcionadas y la resolución predeterminada para la imagen raster escrita en emf (=150).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Ancho de salida de la imagen. |
| altura |  | Altura de salida de la imagen. |

### EmfDevice {#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code EmfDevice} con la resolución predeterminada de la imagen raster escrita en emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-}
Inicializa una nueva instancia de la clase {@code EmfDevice} con la resolución predeterminada de la imagen raster escrita en emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code EmfDevice} con la resolución predeterminada de la imagen raster escrita en emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@code EmfDevice} con la resolución predeterminada de la imagen raster escrita en emf.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convierte la página a emf y la guarda en el flujo de salida.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Convierte la página a emf y la guarda en el flujo de salida.
