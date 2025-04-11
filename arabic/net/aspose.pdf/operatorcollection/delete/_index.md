---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: طريقة OperatorCollection. تحذف المشغل من المجموعة
type: docs
weight: 110
url: /ar/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

تحذف المشغل من المجموعة.

```csharp
public void Delete(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | فهرس المشغل الذي يجب حذفه. يبدأ ترقيم المشغلين من 1. |

## Examples

المثال يوضح كيفية حذف المشغل بواسطة فهرسه.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### See Also

* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

تحذف المشغلين من المجموعة.

```csharp
public void Delete(Operator[] ops)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ops | Operator[] | مصفوفة من المشغلين للحذف |

## Examples

المثال يوضح كيفية إزالة المشغل من محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### See Also

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

تحذف المشغلين من المجموعة.

```csharp
public void Delete(IList<Operator> list)
```

| Parameter | Type | Description |
| --- | --- | --- |
| list | IList`1 | قائمة المشغلين للحذف |

## Examples

المثال يوضح كيفية إزالة المشغل من محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### See Also

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)