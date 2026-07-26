---
title: "DocumentDevice"
linktitle: "DocumentDevice"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Abstrakte Klasse für alle Geräte, die verwendet wird, um das gesamte PDF-Dokument zu verarbeiten."
type: docs
weight: 60
url: /de/java/com.aspose.pdf.devices/documentdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice

```
public abstract class DocumentDevice extends PageDevice
```

Abstrakte Klasse für alle Geräte, die verwendet wird, um das gesamte PDF-Dokument zu verarbeiten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DocumentDevice](#DocumentDevice--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Jedes Gerät stellt eine Operation am Dokument dar, z. B. können wir ein PDF-Dokument in ein anderes Format konvertieren. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Verarbeitet bestimmte Seiten des Dokuments und speichert die Ergebnisse in einer Datei. |
| [process](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | Verarbeitet das gesamte Dokument und speichert die Ergebnisse in einen Stream. |
| [process](#process-com.aspose.pdf.IDocument-java.lang.String-) | Verarbeitet das gesamte Dokument und speichert die Ergebnisse in einer Datei. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Jedes Gerät stellt eine Operation am Dokument dar, z. B. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Verarbeitet das gesamte Dokument und speichert die Ergebnisse in einen Stream. |

### DocumentDevice {#DocumentDevice--}
```
public DocumentDevice()
```



### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Jedes Gerät stellt eine Operation am Dokument dar, z. B. können wir ein PDF-Dokument in ein anderes Format konvertieren.

### process {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
Verarbeitet bestimmte Seiten des Dokuments und speichert die Ergebnisse in einer Datei.

### process {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
Verarbeitet das gesamte Dokument und speichert die Ergebnisse in einen Stream.

### process {#process-com.aspose.pdf.IDocument-java.lang.String-}
Verarbeitet das gesamte Dokument und speichert die Ergebnisse in einer Datei.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Jedes Gerät stellt eine Operation am Dokument dar, z. B.

### processInternal {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Verarbeitet das gesamte Dokument und speichert die Ergebnisse in einen Stream.
