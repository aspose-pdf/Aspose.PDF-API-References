---
title: "OperatorCollection.Add"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OperatorCollection. تُضيف عاملًا جديدًا إلى المجموعة."
type: docs
weight: 60
url: /ar/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

يضيف مشغلًا جديدًا إلى المجموعة.

```csharp
public override void Add(Operator op)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| op | Operator | العامل الذي يجب إضافته. |

## أمثلة

مثال يوضح كيفية إضافة العوامل إلى نهاية page.contents.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### انظر أيضًا

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

يضيف المشغلات في نهاية مشغلات المحتوى.

```csharp
public void Add(Operator[] ops)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ops | Operator[] | مصفوفة من العوامل التي سيتم إضافتها. يمكن لكل عامل أن يكون له أي فهرس (افتراضيًا -1) لأنها تُضاف إلى نهاية عوامل المحتوى أي تُعيّن الفهارس تلقائيًا. |

## أمثلة

مثال يوضح كيفية إضافة عامل إلى نهاية محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### انظر أيضًا

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

يضيف إلى المجموعة جميع المشغلات من مجموعة أخرى.

```csharp
public void Add(ICollection<Operator> ops)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ops | ICollection`1 | مجموعة تحتوي على المشغلات التي سيتم إضافتها. |

## أمثلة

يوضح المثال كيفية إضافة مجموعة المشغلات إلى محتويات الصفحة.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### انظر أيضًا

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


