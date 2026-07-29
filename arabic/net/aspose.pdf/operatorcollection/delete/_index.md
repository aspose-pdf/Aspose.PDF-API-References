---
title: "OperatorCollection.Delete"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OperatorCollection. تحذف المشغل من المجموعة."
type: docs
weight: 110
url: /ar/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

يحذف المشغل من المجموعة.

```csharp
public void Delete(int index)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| index | Int32 | فهرس المشغل الذي يجب حذفه. يبدأ ترقيم المشغلات من 1. |

## أمثلة

يوضح المثال كيفية حذف المشغل وفقًا لفهرسه.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### انظر أيضًا

* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

يحذف المشغلات من المجموعة.

```csharp
public void Delete(Operator[] ops)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ops | Operator[] | مصفوفة المشغلات التي سيتم حذفها |

## أمثلة

يوضح المثال كيفية إزالة المشغل من محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### انظر أيضًا

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

يحذف المشغلات من المجموعة.

```csharp
public void Delete(IList<Operator> list)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| قائمة | IList`1 | قائمة المشغلات التي سيتم حذفها |

## أمثلة

يوضح المثال كيفية إزالة المشغل من محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### انظر أيضًا

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


