---
title: "TextDevice.ExtractionOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextDevice. تحصل أو تعين خيارات استخراج النص"
type: docs
weight: 30
url: /ar/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

يحصل أو يعيّن خيارات استخراج النص.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## أمثلة

يوضح المثال كيفية استخراج النص بترتيب raw.

```csharp
Document doc = new Document(inFile);
string extractedText;

// إنشاء جهاز نصي
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// تحويل الصفحة وحفظ النص إلى الدفق
device.Process(doc.Pages[1], outFile);

// استخدام النص المستخرج
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### انظر أيضًا

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


