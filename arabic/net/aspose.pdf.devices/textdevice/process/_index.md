---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: طريقة TextDevice. تحويل الصفحة وحفظها كتيار نصي
type: docs
weight: 40
url: /ar/net/aspose.pdf.devices/textdevice/process/
---
## طريقة TextDevice.Process

تحويل الصفحة وحفظها كتيار نصي.

```csharp
public override void Process(Page page, Stream output)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| الصفحة | Page | الصفحة التي سيتم تحويلها. |
| الناتج | Stream | تيار النتيجة. |

## أمثلة

المثال يوضح كيفية استخراج النص من الصفحة الأولى لوثيقة PDF.

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

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)