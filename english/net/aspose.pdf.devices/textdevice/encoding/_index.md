---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: TextDevice property. Gets or sets encoding of extracted text
type: docs
weight: 20
url: /net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding property

Gets or sets encoding of extracted text.

```csharp
public Encoding Encoding { get; set; }
```

## Examples

The example demonstrates how to represent extracted text in UTF-8 encoding.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(Encoding.UTF8);

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### See Also

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


