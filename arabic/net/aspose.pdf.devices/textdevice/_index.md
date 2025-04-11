---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Devices.TextDevice. تمثل فئة لتحويل صفحات مستند PDF إلى نص
type: docs
weight: 3680
url: /ar/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

تمثل فئة لتحويل صفحات مستند PDF إلى نص.

```csharp
public sealed class TextDevice : PageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | يقوم بتهيئة مثيل جديد من `TextDevice` مع وضع تنسيق النص الخام وترميز النص Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | يقوم بتهيئة مثيل جديد من `TextDevice` للترميز المحدد. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | يقوم بتهيئة مثيل جديد من `TextDevice` مع خيارات استخراج النص. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | يقوم بتهيئة مثيل جديد من `TextDevice` للترميز المحدد مع خيارات استخراج النص. |

## Properties

| Name | Description |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | يحصل أو يحدد ترميز النص المستخرج. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | يحصل أو يحدد خيارات استخراج النص. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | تحويل الصفحة وحفظها كتيار نص. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | يقوم بإجراء بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

## Remarks

يستخدم كائن `TextDevice` بشكل أساسي لاستخراج النص من صفحة PDF.

## Examples

توضح المثال كيفية استخراج النص من الصفحة الأولى لمستند PDF.

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

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)