---
title: "Font.IsAccessible"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Font. تحصل على ما إذا كان الخط مثبتًا في النظام"
type: docs
weight: 50
url: /ar/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible property

يحصل على ما إذا كان الخط موجودًا (مثبتًا) في النظام.

```csharp
public bool IsAccessible { get; }
```

## ملاحظات

بعض العمليات غير متاحة مع الخطوط التي لا يمكن العثور عليها في النظام.

## أمثلة

يوضح المثال كيفية البحث عن النص في الصفحة الأولى والحصول على القيمة التي تشير إلى ما إذا كان الخط مثبتًا في النظام.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// عرض قيمة IsSubset للخط في أول ظهور للنص
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


