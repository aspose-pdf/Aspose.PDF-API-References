---
title: "DocumentDevice"
linktitle: "DocumentDevice"
second_title: "Aspose.PDF för Java API-referens"
description: "Abstrakt klass för alla enheter som används för att bearbeta hela PDF-dokumentet."
type: docs
weight: 60
url: /sv/java/com.aspose.pdf.devices/documentdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice

```
public abstract class DocumentDevice extends PageDevice
```

Abstrakt klass för alla enheter som används för att bearbeta hela PDF-dokumentet.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [DocumentDevice](#DocumentDevice--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Varje enhet representerar någon operation på dokumentet, t.ex. kan vi konvertera pdf-dokument till ett annat format. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Bearbetar vissa sidor i dokumentet och sparar resultatet i en fil. |
| [process](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | Bearbetar hela dokumentet och sparar resultatet i en ström. |
| [process](#process-com.aspose.pdf.IDocument-java.lang.String-) | Bearbetar hela dokumentet och sparar resultatet i en fil. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Varje enhet representerar någon operation på dokumentet, t.ex. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Bearbetar hela dokumentet och sparar resultatet i en ström. |

### DocumentDevice {#DocumentDevice--}
```
public DocumentDevice()
```



### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Varje enhet representerar någon operation på dokumentet, t.ex. kan vi konvertera pdf-dokument till ett annat format.

### process {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
Bearbetar vissa sidor i dokumentet och sparar resultatet i en fil.

### process {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
Bearbetar hela dokumentet och sparar resultatet i en ström.

### process {#process-com.aspose.pdf.IDocument-java.lang.String-}
Bearbetar hela dokumentet och sparar resultatet i en fil.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Varje enhet representerar någon operation på dokumentet, t.ex.

### processInternal {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Bearbetar hela dokumentet och sparar resultatet i en ström.
