---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: خاصية الوثيقة. تحصل أو تضبط مجموعة من صفحات الوثيقة. لاحظ أن الصفحات مرقمة من 1 في المجموعة
type: docs
weight: 470
url: /ar/net/aspose.pdf/document/pages/
---
## خاصية Document.Pages

تحصل أو تضبط مجموعة من صفحات الوثيقة. لاحظ أن الصفحات مرقمة من 1 في المجموعة.

```csharp
public PageCollection Pages { get; }
```

## أمثلة

المثال أدناه يوضح كيفية العمل مع صفحات الوثيقة: كيفية الحصول على عدد الصفحات وكيفية الحصول على مستطيل الصفحة الأولى من الوثيقة.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### انظر أيضًا

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)