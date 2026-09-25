---
title: "TextDevice Class"
linktitle: "TextDevice"
articleTitle: "TextDevice"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Devices.TextDevice class. Represents class for converting pdf document pages into text."
type: docs
weight: 180
url: "/net/aspose.pdf.devices/textdevice/"
keywords: "TextDevice, Aspose.Pdf.Devices, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextDevice class

Represents class for converting pdf document pages into text.

```csharp
public sealed class TextDevice : PageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [TextDevice](./textdevice/#constructor) | Initializes a new instance of the [`TextDevice`](../../aspose.pdf.devices/textdevice/) with the Raw text formatting mode and Unicode text encoding. |
| [TextDevice](./textdevice/#constructor_1)(*[TextExtractionOptions](../../aspose.pdf.text/textextractionoptions/)*) | Initializes a new instance of the [`TextDevice`](../../aspose.pdf.devices/textdevice/) with text extraction options. |
| [TextDevice](./textdevice/#constructor_2)(*Encoding*) | Initializes a new instance of the [`TextDevice`](../../aspose.pdf.devices/textdevice/) for the specified encoding. |
| [TextDevice](./textdevice/#constructor_3)(*[TextExtractionOptions](../../aspose.pdf.text/textextractionoptions/), Encoding*) | Initializes a new instance of the [`TextDevice`](../../aspose.pdf.devices/textdevice/) for the specified encoding with text extraction options. |

## Properties

| Name | Description |
| --- | --- |
| [Encoding](./encoding/) { get; set; } | Gets or sets encoding of extracted text. |
| [ExtractionOptions](./extractionoptions/) { get; set; } | Gets or sets text extraction options. |

## Methods

| Name | Description |
| --- | --- |
| [Process](./process/)(*Page, Stream*) | Convert page and save it as text stream. |

## Remarks

The [`TextDevice`](../../aspose.pdf.devices/textdevice/) object is basically used to extract text from pdf page.

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

