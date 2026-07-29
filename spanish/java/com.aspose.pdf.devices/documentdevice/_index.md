---
title: "DocumentDevice"
linktitle: "DocumentDevice"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase abstracta para todos los dispositivos que se utiliza para procesar todo el documento pdf."
type: docs
weight: 60
url: /es/java/com.aspose.pdf.devices/documentdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice

```
public abstract class DocumentDevice extends PageDevice
```

Clase abstracta para todos los dispositivos que se utiliza para procesar todo el documento pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [DocumentDevice](#DocumentDevice--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Cada dispositivo representa alguna operación en el documento, p. ej. podemos convertir un documento pdf a otro formato. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Procesa ciertas páginas del documento y guarda los resultados en un archivo. |
| [process](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | Procesa todo el documento y guarda los resultados en un flujo. |
| [process](#process-com.aspose.pdf.IDocument-java.lang.String-) | Procesa todo el documento y guarda los resultados en un archivo. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Cada dispositivo representa alguna operación en el documento, p. ej. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Procesa todo el documento y guarda los resultados en un flujo. |

### DocumentDevice {#DocumentDevice--}
```
public DocumentDevice()
```



### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Cada dispositivo representa alguna operación en el documento, p. ej. podemos convertir un documento pdf a otro formato.

### process {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
Procesa ciertas páginas del documento y guarda los resultados en un archivo.

### process {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
Procesa todo el documento y guarda los resultados en un flujo.

### process {#process-com.aspose.pdf.IDocument-java.lang.String-}
Procesa todo el documento y guarda los resultados en un archivo.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Cada dispositivo representa alguna operación en el documento, p. ej.

### processInternal {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Procesa todo el documento y guarda los resultados en un flujo.
