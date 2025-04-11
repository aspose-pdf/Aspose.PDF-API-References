---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: طريقة OperatorCollection. تضيف مشغلًا جديدًا إلى المجموعة
type: docs
weight: 60
url: /ar/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

تضيف مشغلًا جديدًا إلى المجموعة.

```csharp
public override void Add(Operator op)
```

| Parameter | Type | Description |
| --- | --- | --- |
| op | Operator | المشغل الذي يجب إضافته |

## Examples

المثال يوضح كيفية إضافة مشغلين إلى نهاية محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### See Also

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

إضافة مشغلين إلى نهاية محتويات المشغلين.

```csharp
public void Add(Operator[] ops)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ops | Operator[] | مصفوفة من المشغلين الذين سيتم إضافتهم. يمكن أن يكون لكل مشغل أي فهرس (بشكل افتراضي -1) لأنه يأتي إلى نهاية مشغلين المحتويات أي أن الفهارس تُعين تلقائيًا. |

## Examples

المثال يوضح كيفية إضافة مشغل إلى نهاية محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### See Also

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

تضيف إلى المجموعة جميع المشغلين من مجموعة أخرى.

```csharp
public void Add(ICollection<Operator> ops)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ops | ICollection`1 | مجموعة تحتوي على المشغلين الذين سيتم إضافتهم. |

## Examples

المثال يوضح كيفية إضافة مجموعة مشغلين إلى محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### See Also

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)