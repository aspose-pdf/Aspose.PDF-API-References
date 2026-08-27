---
title: "TextDevice.Encoding"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextDevice. تحصل أو تعين ترميز النص المستخرج"
type: docs
weight: 20
url: /ar/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding property

يحصل أو يضبط ترميز النص المستخرج.

```csharp
public Encoding Encoding { get; set; }
```

## أمثلة

يوضح المثال كيفية تمثيل النص المستخرج بترميز UTF-8.

```csharp
Document doc = new Document(inFile);
string extractedText;

// إنشاء جهاز نصي
TextDevice device = new TextDevice(Encoding.UTF8);

// تحويل الصفحة وحفظ النص إلى الدفق
device.Process(doc.Pages[1], outFile);

// استخدام النص المستخرج
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### انظر أيضًا

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


