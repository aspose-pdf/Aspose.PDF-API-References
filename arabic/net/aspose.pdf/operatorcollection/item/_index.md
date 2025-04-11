---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: خاصية OperatorCollection. يحصل على المشغل بواسطة فهرسه
type: docs
weight: 40
url: /ar/net/aspose.pdf/operatorcollection/item/
---
## فهرس OperatorCollection

يحصل على المشغل بواسطة فهرسه.

```csharp
public override Operator this[int index] { get; set; }
```

| المعامل | الوصف |
| --- | --- |
| index | فهرس المشغل. يبدأ الترقيم من 1. |

### قيمة الإرجاع

المشغل من الفهرس المطلوب

## أمثلة

المثال يوضح كيفية الحصول على مشغل محتويات الصفحة بواسطة الفهرس.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### انظر أيضًا

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)