---
title: "TextAbsorber.Text"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextAbsorber. تحصل على النص المستخرج الذي يقوم TextAbsorber باستخراجه من مستند PDF أو الصفحة"
type: docs
weight: 50
url: /ar/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

يحصل على النص المستخرج الذي يقوم [`TextAbsorber`](../) باستخراجه من مستند PDF أو الصفحة.

```csharp
public virtual string Text { get; }
```

## أمثلة

يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن TextAbsorber لاستخراج النص
TextAbsorber absorber = new TextAbsorber();

// قبول الـ absorber لجميع صفحات المستند
doc.Pages.Accept(absorber);

// احصل على النص المستخرج
string extractedText = absorber.Text;

```

### انظر أيضًا

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


