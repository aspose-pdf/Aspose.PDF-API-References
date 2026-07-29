---
title: "DicomDevice"
linktitle: "DicomDevice"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en formato Dicom."
type: docs
weight: 50
url: /es/java/com.aspose.pdf.devices/dicomdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.DicomDevice

```
public final class DicomDevice extends ImageDevice
```

Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en formato Dicom.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [DicomDevice](#DicomDevice--) | Inicializa una nueva instancia de la clase {@link DicomDevice} con resolución predeterminada. |
| [DicomDevice](#DicomDevice-int-int-) | Inicializa una nueva instancia de la clase {@link DicomDevice} con dimensiones de imagen proporcionadas, con resolución predeterminada (=150). |
| [DicomDevice](#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@link DicomDevice} con resolución predeterminada. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-) | Inicializa una nueva instancia de la clase {@link DicomDevice} con resolución predeterminada. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@link DicomDevice} con resolución predeterminada. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.devices.Resolution-) | Inicializa una nueva instancia de la clase {@link DicomDevice} con resolución predeterminada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convierte la página a Dicom y la guarda en el flujo de salida. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Realiza alguna operación en la página dada, p. ej. |

### DicomDevice {#DicomDevice--}
```
public DicomDevice()
```

Inicializa una nueva instancia de la clase {@link DicomDevice} con resolución predeterminada.

### DicomDevice {#DicomDevice-int-int-}
```
public DicomDevice(int width, int height)
```

Inicializa una nueva instancia de la clase {@link DicomDevice} con dimensiones de imagen proporcionadas, con resolución predeterminada (=150).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Ancho de salida de la imagen. |
| altura |  | Altura de salida de la imagen. |

### DicomDevice {#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@link DicomDevice} con resolución predeterminada.

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-}
Inicializa una nueva instancia de la clase {@link DicomDevice} con resolución predeterminada.

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@link DicomDevice} con resolución predeterminada.

### DicomDevice {#DicomDevice-com.aspose.pdf.devices.Resolution-}
Inicializa una nueva instancia de la clase {@link DicomDevice} con resolución predeterminada.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convierte la página a Dicom y la guarda en el flujo de salida.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Realiza alguna operación en la página dada, p. ej.
