---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: طريقة OperatorCollection. تُدرج المشغل في المجموعة
type: docs
weight: 140
url: /ar/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

تُدرج المشغل في المجموعة.

```csharp
public override void Insert(int index, Operator op)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | الفهرس الذي يجب إضافة المشغل الجديد فيه |
| op | Operator | المشغل الذي سيتم إدراجه |

## Examples

توضح هذه المثال كيفية إدراج مشغل في محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### See Also

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

إدراج المشغلين في الموضع المحدد.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parameter | Type | Description |
| --- | --- | --- |
| at | Int32 | الفهرس الذي يبدأ منه إدراج المشغلين. |
| ops | Operator[] | مصفوفة من المشغلين الذين سيتم إدراجهم. يمكن أن يكون لكل مشغل أي فهرس (بشكل افتراضي -1) لأن فهارسهم تتكيف تلقائيًا بدءًا من *at*. |

## Examples

توضح هذه المثال كيفية إدراج مشغل في محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### See Also

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

إدراج المشغلين في الموضع المحدد.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parameter | Type | Description |
| --- | --- | --- |
| at | Int32 | الفهرس الذي يبدأ منه إدراج المشغلين. |
| ops | IList`1 | مصفوفة من المشغلين الذين سيتم إدراجهم. |

## Examples

توضح هذه المثال كيفية إدراج المشغلين في محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### See Also

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)