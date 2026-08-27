---
title: "Page.Contents"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Page. يحصل على مجموعة من المشغلات في تدفق محتوى الصفحة. OperatorCollection"
type: docs
weight: 90
url: /ar/net/aspose.pdf/page/contents/
---
## Page.Contents property

يحصل على مجموعة من المشغلات في تدفق محتوى الصفحة. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## أمثلة

المثال يوضح كيفية مسح تدفق المشغلات للصفحة.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### انظر أيضًا

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


