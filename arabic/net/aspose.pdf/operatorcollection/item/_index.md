---
title: "OperatorCollection.Item"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية OperatorCollection. تحصل على المشغل حسب فهرسه"
type: docs
weight: 40
url: /ar/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

يحصل على المشغل حسب فهرسه.

```csharp
public override Operator this[int index] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| index | فهرس المشغل. يبدأ الترقيم من 1. |

### قيمة الإرجاع

المشغل من الفهرس المطلوب

## أمثلة

يوضح المثال كيفية الحصول على مشغل محتويات الصفحة حسب الفهرس.

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


