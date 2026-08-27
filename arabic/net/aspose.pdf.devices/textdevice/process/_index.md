---
title: "TextDevice.Process"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة TextDevice. تحويل الصفحة وحفظها كتيار نصي"
type: docs
weight: 40
url: /ar/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process method

تحويل الصفحة وحفظها كتدفق نص.

```csharp
public override void Process(Page page, Stream output)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | صفحة | الصفحة للتحويل. |
| الإخراج | Stream | تيار النتيجة. |

## أمثلة

يوضح المثال كيفية استخراج النص من الصفحة الأولى لـ PDF document.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // إنشاء جهاز نصي
    TextDevice device = new TextDevice();

    // تحويل الصفحة وحفظ النص إلى الدفق
    device.Process(doc.Pages[1], ms);

    // استخدام النص المستخرج
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


