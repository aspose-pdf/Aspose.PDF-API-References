---
title: DocumentDevice
second_title: Aspose.PDF for Java API Reference
description: Abstract class for all devices which is used to process the whole pdf document.
type: docs
weight: 14
url: /java/com.aspose.pdf.devices/documentdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device)
```
public abstract class DocumentDevice extends Device
```

Abstract class for all devices which is used to process the whole pdf document.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentDevice()](#DocumentDevice--) |  |
## Methods

| Method | Description |
| --- | --- |
| [processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Each device represents some operation on the document, e.g. we can convert pdf document into another format. |
| [process(IDocument document, int fromPage, int toPage, OutputStream output)](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) |  |
| [process(IDocument document, int fromPage, int toPage, System.IO.Stream output)](#process-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) |  |
| [processInternal(IDocument document, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Processes the whole document and saves results into stream. |
| [process(IDocument document, OutputStream output)](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) |  |
| [process(IDocument document, String outputFileName)](#process-com.aspose.pdf.IDocument-java.lang.String-) | Processes the whole document and saves results into file. |
| [process(IDocument document, int fromPage, int toPage, String outputFileName)](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Processes certain pages of the document and saves results into file. |
### DocumentDevice() {#DocumentDevice--}
```
public DocumentDevice()
```


### processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
```
public abstract void processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)
```


Each device represents some operation on the document, e.g. we can convert pdf document into another format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The document to process. |
| fromPage | int | Defines the page from which to start processing. |
| toPage | int | Defines the last page to process. |
| output | com.aspose.ms.System.IO.Stream | Defines stream where the results of processing are stored. |

### process(IDocument document, int fromPage, int toPage, OutputStream output) {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
```
public void process(IDocument document, int fromPage, int toPage, OutputStream output)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) |  |
| fromPage | int |  |
| toPage | int |  |
| output | java.io.OutputStream |  |

### process(IDocument document, int fromPage, int toPage, System.IO.Stream output) {#process-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
```
public void process(IDocument document, int fromPage, int toPage, System.IO.Stream output)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) |  |
| fromPage | int |  |
| toPage | int |  |
| output | com.aspose.ms.System.IO.Stream |  |

### processInternal(IDocument document, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(IDocument document, System.IO.Stream output)
```


Processes the whole document and saves results into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The document to process. |
| output | com.aspose.ms.System.IO.Stream | Defines stream where the results of processing are stored. |

### process(IDocument document, OutputStream output) {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public void process(IDocument document, OutputStream output)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) |  |
| output | java.io.OutputStream |  |

### process(IDocument document, String outputFileName) {#process-com.aspose.pdf.IDocument-java.lang.String-}
```
public void process(IDocument document, String outputFileName)
```


Processes the whole document and saves results into file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The document to process. |
| outputFileName | java.lang.String | Defines file where the results of processing are stored. |

### process(IDocument document, int fromPage, int toPage, String outputFileName) {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
```
public void process(IDocument document, int fromPage, int toPage, String outputFileName)
```


Processes certain pages of the document and saves results into file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The document to process. |
| fromPage | int | The first page to start processing. |
| toPage | int | The last page of processing. |
| outputFileName | java.lang.String | Defines file where the results of processing are stored. |

