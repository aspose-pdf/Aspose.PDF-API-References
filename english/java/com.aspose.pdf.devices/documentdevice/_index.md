---
title: DocumentDevice
linktitle: DocumentDevice
second_title: Aspose.PDF for Java API Reference
description: Abstract class for all devices which is used to process the whole pdf document.
type: docs
weight: 60
url: /java/com.aspose.pdf.devices/documentdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice

```
public abstract class DocumentDevice extends PageDevice
```

Abstract class for all devices which is used to process the whole pdf document.

## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentDevice](#DocumentDevice--) |  |

## Methods

| Method | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Each device represents some operation on the document, e.g. we can convert pdf document into another format. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Processes certain pages of the document and saves results into file. |
| [process](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | Processes the whole document and saves results into stream. |
| [process](#process-com.aspose.pdf.IDocument-java.lang.String-) | Processes the whole document and saves results into file. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Each device represents some operation on the document, e.g. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Processes the whole document and saves results into stream. |

### DocumentDevice {#DocumentDevice--}
```
public DocumentDevice()
```



### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Each device represents some operation on the document, e.g. we can convert pdf document into another format.

### process {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
Processes certain pages of the document and saves results into file.

### process {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
Processes the whole document and saves results into stream.

### process {#process-com.aspose.pdf.IDocument-java.lang.String-}
Processes the whole document and saves results into file.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Each device represents some operation on the document, e.g.

### processInternal {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Processes the whole document and saves results into stream.
