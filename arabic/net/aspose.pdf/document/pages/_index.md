---
title: "Document.Pages"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Document. يحصل على أو يضبط مجموعة صفحات المستند. لاحظ أن الصفحات مرقمة بدءًا من 1 في المجموعة."
type: docs
weight: 490
url: /ar/net/aspose.pdf/document/pages/
---
## Document.Pages property

يحصل أو يضبط مجموعة صفحات المستند. لاحظ أن الصفحات مُرقَّمة بدءًا من 1 في المجموعة.

```csharp
public PageCollection Pages { get; }
```

## أمثلة

المثال أدناه يوضح كيفية التعامل مع صفحات المستند: كيفية الحصول على عدد الصفحات وكيفية الحصول على مستطيل الصفحة الأولى من المستند.

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


