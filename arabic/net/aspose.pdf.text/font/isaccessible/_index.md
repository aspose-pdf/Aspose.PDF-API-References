---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: خاصية الخط. تحصل على ما يشير إلى ما إذا كان الخط مثبتًا في النظام
type: docs
weight: 50
url: /ar/net/aspose.pdf.text/font/isaccessible/
---
## خاصية Font.IsAccessible

تحصل على ما يشير إلى ما إذا كان الخط موجودًا (مثبتًا) في النظام.

```csharp
public bool IsAccessible { get; }
```

## ملاحظات

بعض العمليات غير متاحة مع الخطوط التي لم يمكن العثور عليها في النظام.

## أمثلة

المثال يوضح كيفية البحث عن نص في الصفحة الأولى والحصول على القيمة التي تشير إلى ما إذا كان الخط مثبتًا في النظام.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)