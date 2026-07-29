---
title: "TextAbsorber.ExtractionOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextAbsorber. تحصل على أو تعيين خيارات استخراج النص"
type: docs
weight: 30
url: /ar/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions property

يحصل أو يعيّن خيارات استخراج النص.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## ملاحظات

يسمح بتعريف وضع تنسيق النص [`TextExtractionOptions`](../../textextractionoptions/) أثناء الاستخراج. الوضع الافتراضي هو Pure

## أمثلة

يوضح المثال كيفية تعيين وضع تنسيق النص Pure وتنفيذ استخراج النص.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن TextAbsorber لاستخراج النص مع التنسيق
TextAbsorber absorber = new TextAbsorber();

// تعيين وضع تنسيق النص Pure
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// قبول الـ absorber لجميع صفحات المستند
doc.Pages.Accept(absorber);

// احصل على النص المستخرج
string extractedText = absorber.Text;
```

### انظر أيضًا

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


