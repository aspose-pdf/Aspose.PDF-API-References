---
title: "Font.FontName"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Font. تحصل على اسم الخط لكائن Font"
type: docs
weight: 30
url: /ar/net/aspose.pdf.text/font/fontname/
---
## Font.FontName property

يحصل على اسم الخط لكائن [`Font`](../).

```csharp
public string FontName { get; }
```

## أمثلة

يوضح المثال كيفية البحث عن النص في الصفحة الأولى وعرض اسم الخط لأول ظهور للنص.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// عرض اسم الخط لأول ظهور للنص
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


