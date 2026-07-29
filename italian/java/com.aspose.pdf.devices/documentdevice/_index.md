---
title: "DocumentDevice"
linktitle: "DocumentDevice"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe astratta per tutti i dispositivi utilizzata per elaborare l'intero documento pdf."
type: docs
weight: 60
url: /it/java/com.aspose.pdf.devices/documentdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice

```
public abstract class DocumentDevice extends PageDevice
```

Classe astratta per tutti i dispositivi utilizzata per elaborare l'intero documento pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DocumentDevice](#DocumentDevice--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Ogni dispositivo rappresenta qualche operazione sul documento, ad es. possiamo convertire un documento pdf in un altro formato. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Elabora alcune pagine del documento e salva i risultati in un file. |
| [process](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | Elabora l'intero documento e salva i risultati in un flusso. |
| [process](#process-com.aspose.pdf.IDocument-java.lang.String-) | Elabora l'intero documento e salva i risultati in un file. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Ogni dispositivo rappresenta qualche operazione sul documento, ad es. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Elabora l'intero documento e salva i risultati in un flusso. |

### DocumentDevice {#DocumentDevice--}
```
public DocumentDevice()
```



### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Ogni dispositivo rappresenta qualche operazione sul documento, ad es. possiamo convertire un documento pdf in un altro formato.

### process {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
Elabora alcune pagine del documento e salva i risultati in un file.

### process {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
Elabora l'intero documento e salva i risultati in un flusso.

### process {#process-com.aspose.pdf.IDocument-java.lang.String-}
Elabora l'intero documento e salva i risultati in un file.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Ogni dispositivo rappresenta qualche operazione sul documento, ad es.

### processInternal {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Elabora l'intero documento e salva i risultati in un flusso.
