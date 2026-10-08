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
product_version: "26.9"
---
## TextDevice class

Represents class for converting pdf document pages into text.

```csharp
public sealed class TextDevice : PageDevice
```

## Examples

The example demonstrates how to extract text on the first PDF document page.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

## Constructors

| Name | Description |
| --- | --- |
| [TextDevice](textdevice/#constructor)(TextExtractionOptions) | Initializes a new instance of the `TextDevice` with text extraction options. |
| [TextDevice](textdevice/#constructor_1)() | Initializes a new instance of the `TextDevice` with the Raw text formatting mode and Unicode text encoding. |
| [TextDevice](textdevice/#constructor_2)(Encoding) | Initializes a new instance of the `TextDevice` for the specified encoding. |
| [TextDevice](textdevice/#constructor_3)(TextExtractionOptions, Encoding) | Initializes a new instance of the `TextDevice` for the specified encoding with text extraction options. |

## Properties

| Name | Description |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Gets or sets encoding of extracted text. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Gets or sets text extraction options. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/)(Page, Stream) | Convert page and save it as text stream. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Perfoms some operation on the given page and saves results into the file. |

## Remarks

The [`TextDevice`](../textdevice/) object is basically used to extract text from pdf page.

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)

