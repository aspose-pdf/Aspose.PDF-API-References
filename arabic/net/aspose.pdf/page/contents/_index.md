---
title: Contents
second_title: Aspose.PDF لمرجع .NET API
description: يحصل على مجموعة من العوامل في دفق محتوى الصفحة.OperatorCollectionaspose.pdf/operatorcollection
type: docs
weight: 90
url: /ar/net/aspose.pdf/page/contents/
---
## Page.Contents property

يحصل على مجموعة من العوامل في دفق محتوى الصفحة.[`OperatorCollection`](../../operatorcollection)

```csharp
public OperatorCollection Contents { get; }
```

### أمثلة

المثال يوضح كيفية مسح تيار المشغلين للصفحة.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### أنظر أيضا

* class [OperatorCollection](../../operatorcollection)
* class [Page](../../page)
* مساحة الاسم [Aspose.Pdf](../../page)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->