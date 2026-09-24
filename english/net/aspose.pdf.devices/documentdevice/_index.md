---
title: "DocumentDevice Class"
linktitle: "DocumentDevice"
articleTitle: "DocumentDevice"
second_title: "Aspose.PDF for .NET"
description: "Abstract class for all devices which is used to process the whole pdf document."
type: docs
weight: 70
url: "/net/aspose.pdf.devices/documentdevice/"
keywords: "DocumentDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## DocumentDevice class

Abstract class for all devices which is used to process the whole pdf document.

```csharp
public abstract class DocumentDevice : PageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [DocumentDevice](./documentdevice/#constructor) | Initializes a new instance of the DocumentDevice class. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.devices/device/document/) { get; set; } | Document which is processed by this device instance. *(Inherited from Device)* |

## Methods

| Name | Description |
| --- | --- |
| [Process](./process/)(*Document, Stream*) | Processes the whole document and saves results into stream. |
| [Process](./process/)(*Document, string*) | Processes the whole document and saves results into file. |
| [Process](./process/)(*Document, int, int, Stream*) | Each device represents some operation on the document, e.g. we can convert pdf document into another format. |
| [Process](./process/)(*Document, int, int, string*) | Processes certain pages of the document and saves results into file. |

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

