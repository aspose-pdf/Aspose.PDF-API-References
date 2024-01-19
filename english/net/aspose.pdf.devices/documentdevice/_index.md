---
title: Class DocumentDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DocumentDevice class. Abstract class for all devices which is used to process the whole pdf document
type: docs
weight: 1720
url: /net/aspose.pdf.devices/documentdevice/
---
## DocumentDevice class

Abstract class for all devices which is used to process the whole pdf document.

```csharp
public abstract class DocumentDevice : Device
```

## Methods

| Name | Description |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/documentdevice/binarizebradley/)(Stream, Stream, double) | Do Bradley binarization for input stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | Processes the whole document and saves results into stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | Processes the whole document and saves results into file. |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | Each device represents some operation on the document, e.g. we can convert pdf document into another format. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | Processes certain pages of the document and saves results into file. |

### See Also

* class [Device](../device/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


