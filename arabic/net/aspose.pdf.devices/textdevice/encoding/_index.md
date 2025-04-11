---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextDevice. تحصل أو تعين ترميز النص المستخرج
type: docs
weight: 20
url: /ar/net/aspose.pdf.devices/textdevice/encoding/
---
## خاصية TextDevice.Encoding

تحصل أو تعين ترميز النص المستخرج.

```csharp
public Encoding Encoding { get; set; }
```

## أمثلة

توضح المثال كيفية تمثيل النص المستخرج في ترميز UTF-8.

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

### انظر أيضًا

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)