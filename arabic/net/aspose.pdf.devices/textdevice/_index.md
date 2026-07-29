---
title: "الفئة TextDevice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Devices.TextDevice. تمثل فئة لتحويل صفحات مستند pdf إلى نص."
type: docs
weight: 3800
url: /ar/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

يمثل فئة لتحويل صفحات مستند pdf إلى نص.

```csharp
public sealed class TextDevice : PageDevice
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | يقوم بتهيئة نسخة جديدة من `TextDevice` مع وضع تنسيق النص الخام وترميز النص Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | يقوم بتهيئة نسخة جديدة من `TextDevice` للترميز المحدد. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | يقوم بتهيئة نسخة جديدة من `TextDevice` مع خيارات استخراج النص. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | يقوم بتهيئة نسخة جديدة من `TextDevice` للترميز المحدد مع خيارات استخراج النص. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | يحصل أو يضبط ترميز النص المستخرج. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | يحصل أو يعيّن خيارات استخراج النص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | تحويل الصفحة وحفظها كتدفق نص. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفّذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## ملاحظات

كائن `TextDevice` يُستخدم أساسًا لاستخراج النص من صفحة pdf.

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

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


