---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextDevice. الحصول على خيارات استخراج النص أو تعيينها
type: docs
weight: 30
url: /ar/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## خاصية TextDevice.ExtractionOptions

الحصول على خيارات استخراج النص أو تعيينها.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## أمثلة

توضح المثال كيفية استخراج النص بالترتيب الخام.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### انظر أيضًا

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)