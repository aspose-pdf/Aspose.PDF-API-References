---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: خاصية الصفحة. تحصل على مجموعة من العوامل في تدفق محتوى الصفحة. OperatorCollection
type: docs
weight: 90
url: /ar/net/aspose.pdf/page/contents/
---
## خاصية محتويات الصفحة

تحصل على مجموعة من العوامل في تدفق محتوى الصفحة. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## أمثلة

المثال يوضح كيفية مسح تدفق العوامل للصفحة.

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